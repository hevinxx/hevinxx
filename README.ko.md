# 문해빈

[![en](https://img.shields.io/badge/lang-en-red.svg)](https://github.com/hevinxx/hevinxx/blob/main/README.md)

안드로이드 소프트웨어 엔지니어 | 2018년 ~  
[https://linktr.ee/hevinxx](https://linktr.ee/hevinxx)  
[https://hevinxx.github.io](https://hevinxx.github.io/)  
[hevinxx@gmail.com](mailto:hevinxx@gmail.com)

국어국문학과 수학을 전공하고 뮤지션을 꿈꾸다 개발자가 되었습니다. 서로 다른 분야들이지만 공통된 특성은 모두 일종의 언어라는 점입니다. 코드는 컴퓨터가 읽기 위한 것이 아니라 사람이 읽기 위한 것이라고 믿습니다. 또 엔지니어의 일은 프로그램을 만드는 일이 아니라 코드를 만드는 일이라 생각합니다. 그래서 '가독성'을 중요하게 여기며 일하고 있습니다. 읽기 좋은 코드를 통해 개발자와 소통을 잘하는 것 뿐만 아니라, 비개발자와도 가장 알기 쉽게 커뮤니케이션을 잘하는 개발자로 몸담았던 회사들에서 인정받아 왔습니다.

## 기술 스택

### 익숙함
- Android
- Kotlin
- Jetpack Compose, RX, Coroutine, Hilt, Retrofit2, Glide
- MVVM
- Github, Bitbucket, Jira, Zeplin, Figma, Slack, Gather

### 경험해 봄
- Flutter
- Java, Scala, JavaScript, TypeScript, Python, Dart
- Koin, Coil, Jetpack Navigation
- MVP
- PostgreSQL, Firebase Realitme Database, Room, Realm
- Socket.IO, React Native, AWS, Docker, Node.js, Express, Sequelize, Chai, Spark

## 주요 프로젝트

### Jetpack Compose 마이그레이션 @바비톡 | 2024년

- 안드로이드 뷰 기반으로 되어 있던 앱을 1년 여에 걸쳐 Jetpack Compose로 마이그레이션
- 특히 RecyclerView에 얽혀 있던 각종 기능들을 전담하여 리팩토링
- 기존의 로직을 Jetpack Compose에 맞게 '해석'하는 데에 그치지 않고, 명령형으로 구현되어 있던 기능을 선언형으로, 함수형 프로그래밍에 걸맞게 '번역'하는 과정이 필요했음

### 모션형 배너 @바비톡 | 2023년 9월(안드로이드 뷰), 2024년 4월 ~ 5월(Jetpack Compose)

- 고객이 등록한 이미지에 애니메이션을 적용하여 화려한 효과를 부여
- 처음엔 안드로이드 뷰를 기반으로 개발하여, 이미지 뷰를 포함한 뷰홀더에 개발하였으나 후에 앱을 Jetpack Compose로 마이그레이션 하면서 Jetpack Compose 기반으로 다시 개발
- 안드로이드 뷰 기반 개발 시에는 ImageMatrix를 조작하는 방식으로 구현
- Jetpack Compose 기반 개발 시에는 ContentScale을 커스텀 구현
- 이미지 캐시에 대한 이해가 필요했던 작업

### 만보기 기능 @킬로(밀리그램 앱) | 2023년 1월

- Service, Broadcast Receiver 등의 안드로이드 컴포넌트를 활용하여 만보기 기능을 직접 구현
- Realm DB를 활용해 디바이스에 걷기 기록을 저장하고 이를 서버와 싱크

### 식단, 운동 데이터 공유 기능 @킬로(밀리그램 앱) | 2022년 5월

- 유저의 식단 및 운동 데이터를 모아 이미지를 구성하여, 세 가지 타입의 이미지로 외부에 공유할 수 있게 한 기능
- 이미지를 구성하는 데에는 Jetpack Compose 활용
- 다양한 데이터를 한 데 모으면서, 각 데이터를 포함, 제외하는 등의 조작을 다양한 상황에서 오류없이 구현하는 데에 MVVM 구조가 큰 도움이 됨

### 인앱 결제 기능 @킬로(밀리그램 앱) | 2022년 3월 ~ 4월

- 구독 결제를 통해 밀리그램 앱의 프로 기능을 해금
- 유저의 결제 여부가 앱 내 모든 화면에서 알맞게 싱크되어 각 기능을 보여주거나 감춤
- 오류 처리, 리트라이 로직 등 구현

### 다노핏 @다노 | 2021년 6월 ~ 9월

- 챗봇을 개발하여 이를 통해 유저의 체력 수준, 목표 강도, 운동 경험 등을 파악
- 챗봇 구현에는 연결 리스트, 큐와 같은 자료 구조에 관한 지식이 큰 도움이 됨
- 챗봇은 Socket.IO를 기반으로 개발
- 구독 서비스를 통해 운동 영상을 포함한 다양한 식단, 운동 정보를 매일 제공
- 운동 영상 재생 정보를 기반으로 달성도 계산

## 회사 경력

### (주)바비톡 | 안드로이드 앱 개발 | 2023년 5월 ~

바비톡: 다운로드 700만 이상, 월간 사용자 수 100만 이상의 성형/시술 정보 앱
안드로이드 앱 개발 외에도, 'AI 퍼실리테이터'로 활동하며 AI 활용을 통한 생산성 향상 연구 및 발표

### (주)킬로 | 안드로이드 앱 개발 | 2022년 2월 ~ 2023년 1월

밀리그램: 구글플레이 2022 올해를 빛낸 자기계발 앱 우수상. 국내 식단 기록 분야 앱스토어, 구글플레이 동시 1위. 누적 100만 다운로드

### (주)다노 | 소프트웨어 개발 | 2018년 10월 ~ 2022년 1월

2년 연속 올해의 브랜드 대상 수상 여성 토탈 다이어트 솔루션
- 2018년 10월: 백엔드 개발자로 입사
- 2018년 11월 ~ 2019년 8월: 데이터 엔지니어로서 사내 데이터 대시보드 개발
- 2019년 5월 ~ 2022년 1월: 안드로이드 앱 개발자로서 다노 앱 개발

## 사이드 프로젝트

### [VisibilityTracker](https://github.com/hevinxx/visibility-tracker) | 2024년 3월 ~
- Jetpack Compose 라이브러리
- Composable이 유저에게 일정 비율 이상 노출되었을 경우를 감지
- 개발 과정에서의 고민과 문제점, 해결책, 한계 등을 [블로그](https://hevinxx.github.io/%EA%B0%9C%EB%B0%9C/2024/03/02/%EC%95%88%EB%93%9C%EB%A1%9C%EC%9D%B4%EB%93%9C-%EC%95%B1%EC%97%90%EC%84%9C-%EC%8A%A4%ED%81%AC%EB%A1%A4-%EB%82%B4-%ED%99%94%EB%A9%B4-%EB%85%B8%EC%B6%9C-%EC%B6%94%EC%A0%81%ED%95%98%EA%B8%B0.html)로 작성

### 10p ([Google Play](https://play.google.com/store/apps/details?id=io.hevinxx.one_o_p) [App Store](https://apps.apple.com/kr/app/10p/id1671311718)) | 2023년 1월 ~

- 사이드 프로젝트로 홀로 개발한 독서 기록 앱
- 앱은 Flutter를 통해 구현하였고, 데이터는 Firebase Realtime Database를 활용함

### 슬립온잇 (현재 운영 중지) | 2020년 6월 ~ 2022년 3월

- 데이팅 앱으로 플레이스토어, 앱스토어 출시했으나 현재는 운영 중지
- Flutter를 활용해 앱 개발
- Node.js와 Typescript 활용해 백엔드 개발
- Socket.IO를 활용해 채팅 기능 개발

## 창작 활동

### [페퍼노트](https://maily.so/pepper.note)

'그런 건 어떻게 알았어?' 할 때 '그런 것'들을 전해 드리는 뉴스레터. 발송한 뉴스레터 약 200건, 구독자 1,600명 이상, 누적 조회 수 60만 이상.

### 작곡

개발자가 되기 전, 뮤지션이 되길 꿈꿔 작곡 활동. 
- [이런 노래](https://youtu.be/iraqAN7sH9g?si=MGCakUEzfpjWSOwm)
- [끝](https://youtu.be/0vbhKz5D6Xs?si=SlAf5lDa06CPoEDW)
- [용건만 간단히](https://youtu.be/SGqsWEd7e3Q?si=YicGqK85tE5r7BlZ)
- [SoundCloud](https://soundcloud.com/hevinxx)

### [AI Art](https://www.instagram.com/hevin_aug7)

챗GPT, DALL-E를 활용하여 미술 활동

## 학력

- 고려대학교 문학사(국어국문학) | 2012년 ~ 2019년
- 고려대학교 이학사(수학) | 2012년 ~ 2019년
- 한영외국어고등학교 스페인어과 | 2008년 ~ 2011년