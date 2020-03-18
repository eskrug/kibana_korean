# kibana_korean

kibana에서는 기본적으로 영어를 지원하고, 공식적으로 일본어/중국어를 지원하고 있습니다.

아직 한국어는 지원이 되지 않고 있어 일본어 파일을 구글번역 API를 통해 자동으로 번역하여 한글용 파일을 만들었습니다.
따라서 번역 퀄리티가 부족한 부분이 있습니다.

Kibana version 7.6.1을 기준으로 작성되었습니다.

## 셋팅방법
1) create folder) KIBANA_HOME/x-pack/translations
2) create file) KIBANA_HOME/x-pack/.i18nrc.json
3) create file) KIBANA_HOME/x-pack/translations/ko-KR.json
4) add line into kibana.yml) i18n.locale: "ko-KR" 


.i18nrc.json

```
{

  "exclude": [

  ],

  "translations": [

    "translations/ko-KR.json"

  ]

}
```

## 수정 참여 부탁
사용하시면서 수정이 필요한 부분이 보이면 언제든지 수정에 참여해주시기 바랍니다.
힘을 합쳐 키바나에서 보다 나은 한국어 지원이 가능하도록 발전시켰으면 좋겠습니다.


