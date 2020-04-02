# kibana_korean

kibana에서는 기본적으로 영어를 지원하고, 공식적으로 일본어/중국어를 지원하고 있습니다.

아직 한국어는 지원이 되지 않고 있어 일본어 파일을 구글번역 API를 통해 자동으로 번역하여 한글용 파일을 만들었습니다.
따라서 번역 퀄리티가 부족한 부분이 있습니다.

Kibana version 7.6.1을 기준으로 작성되었습니다.

## 셋팅방법
1) KIBANA_HOME/x-pack/.i18nrc.json 파일에 한국어 파일 추가
```
  "translations": [
    "plugins/translations/translations/zh-CN.json",
    "plugins/translations/translations/ja-JP.json",
    "plugins/translations/translations/ko-KR.json"
  ]
```
2) create file) KIBANA_HOME/x-pack/plugins/translations/translations/ko-KR.json
3) kibana.yml에 locale 셋팅 추가
```
i18n.locale: "ko-KR" 
```

## 수정 참여 부탁
사용하시면서 수정이 필요한 부분이 보이면 언제든지 수정에 참여해주시기 바랍니다.
많은 분들이 참여하여 키바나에서 보다 나은 한국어 지원이 가능하도록 발전시켰으면 좋겠습니다.

### 수정 요청 방법
#### 1) ko-KR.json 수정 후 pull request
#### 2) 이슈 생성
- issue tap에서 `new issue` 클릭
  ![issue create](https://github.com/eskrug/kibana_korean/blob/master/img/1.png "issue create")
- 아래의 예시와 같이 내용 작성
  ![issue contents](https://github.com/eskrug/kibana_korean/blob/master/img/2.png "issue context")
```
<< title >>
ko-KR.json 내용 수정

<< contents >> 
url : http://localhost:5601/app/kibana#/home
current text : 데이터 세트와 Kibana 대시 보드를로드
tobe text : 데이터와 Kibana 대시보드 로드
```
