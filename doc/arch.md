아직 논의중인 문서입니다!

참여자 중 한 명이 멋대로 작성한 문서입니다. 마음껏 수정해주세요.

# Architecture

jupyter와 비슷하게 갑니다.

1. 사용자는 자신의 컴퓨터에서 백그라운드로 서버를 실행시켜서, 웹으로 이용하는 것을 전재합니다.
2. 주피터에서 그러하듯이, 원한다면 외부에서도 접속할 수 있도록 합니다.
3. 1차적인 목표는, html문서에서 번역할 부분을 파싱해와서 replace 할 수 있도록 하는 것입니다.

### API

Django framework를 사용해서 JSON Request/Response 형식의 API Server를 만듭니다.
동시에 프론트엔드 프레임워크에서 빌드된 static파일들에 대한 servlet기능도 겸합니다.

### Client

React.js 프레임워크를 사용합니다.
