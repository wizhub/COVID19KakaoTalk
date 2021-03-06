# COVID19KakaoTalk
코로나19 직원 헬스체커 자동화 프로세스 

# 추가 및 변경 사항 
- What'sApp 과 Faceboo Workplace 메신저가 추가되었습니다. ( 기본 설정은 KakaoTalk 입니다. Data\Config.xls의 MessengerApp 부분 참고) 
현재 지원하는 메신저는 카카오톡(KakaoTalk), 와츠앱(Whatsapp), 워크플레이스(Workplace) 3종입니다. 
- 실행시 메신저 종류와 주소록을 지정할수 있도록 추가했습니다. ( in_MessengerApp, in_Addressbook 인수 사용)
- WhatsApp 사용시 카카오톡과 유사하게 태스크바에 바로가기를 추가해주세요. 

# 최신 릴리즈는 1.0.26 입니다. 
- releases 부분에서 nuget package 다운로드 받아 사용하세요. 
- 전체 코드를 내려받아 배포하셔도 됩니다. 
- 패키지버전과 release 버전을 통일하도록 변경했습니다. 
- 주소록에 보낸 날짜 컬럼을 추가했습니다.

# 매뉴얼 
- Docs 폴더에 보면 헬스체커 프로세스 적용 방안이 설명되어 있습니다. 

# 사전 준비사항 
- Windows PC ( Win10 메모리 8G 권장) 1대 이상 
- 카카오톡 계정 ( 데이터 나눠쓰기, 공기계를 이용해서 별도로 번호를 하나 받으세요)
- Microsoft 계정 ( 건강체크에 사용하는 MS Forms 생성/관리에 필요) 
- Microsoft Store에서 카카오톡 다운로드 및 설치 
- <del>Microsoft Excel 설치</del> 
- 설문 내용 준비 및 설문 등록 : Microsoft Forms 이용 
- 오케스트레이터가 없으신 분들은 https://cloud.uipath.com 에서 Community Edition Orchestrator Tenant 생성 

* 자세한 사용법은 COVID19헬스체커.pdf 문서를 참고하세요.
