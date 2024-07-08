# 🎬 홀릭컬쳐
<img src="https://github.com/Holiculture/Holiculture_iOS/assets/126135097/9f0cc60c-8c2e-437f-bf2b-97a89fc96331" width="100" height="100"/>

### 공연장의 위치를 기반하여 주변 장소(식당, 숙소, 즐길거리)를 추천해주는 앱
- iOS 1인 개발 / BackEnd 협업
- 최소 버전 iOS 16.2
- 개발 기간 7주 (2023.07.01 ~ 2034.08.20)

## 📝 주요 기능
- 사용자 티켓 정보 등록 및 수정
- 등록된 티켓 장소 주변 시설 추천
- 추천 장소 스크랩 기능
- 스크랩 장소에 대한 경로 찾기 기능
- 접속일 기준 상연중인 공연 리스트 제공

## ⚒️ 사용 기술 및 라이브러리
`SwiftUI` `Alamofire` `TAKUUID` `AppStorage` `UIViewRepresentable` `MVC` `UIApplication` `UNUserNotificationCenter` `Singleton`


## ⚒️ 기술 적용
- **UIViewRepresentable**을 통해 SwiftUI에서 WebView 구현
- **@AppStorage**를 통해 유저의 알림 설정 타입 여부를 저장하여 사용
- **scenePhase**를 통해 앱의 scene 상태에 대하여 대응
- **UNUserNotificationCenter**를 통해 사용자에게 공연 시작 시간에 대한 알림 제공
- **UIApplication**을 통해 제공된 URL을 열도록 구현 (디바이스에 카카오맵이 없다면 애플 맵으로 대체)
- **CustomView**를 통해 중복된 코드를 줄이고 뷰의 재사용성을 높임
- **Singleton** 패턴을 통해 티켓 관리와 관련된 기능에 접근하도록 구현하여 메모리 사용 최적화


## 📷 스크린샷
|등록된 티켓|공연 검색|공연 상세정보|현재 상영중인 공연|
|:---:|:---:|:---:|:---:|
|<img src="https://github.com/Holiculture/Holiculture_iOS/assets/126135097/9cee3c55-81b3-4419-9cd5-b619f854f1b7" width="200" height="390"/>|<img src="https://github.com/Holiculture/Holiculture_iOS/assets/126135097/d8764c12-3cb0-41e5-8732-19eb2871a332" width="200" height="390"/>|<img src="https://github.com/Holiculture/Holiculture_iOS/assets/126135097/6424e1aa-ceeb-443a-a0e7-4d9fb8bab709" width="200" height="390"/>|<img src="https://github.com/Holiculture/Holiculture_iOS/assets/126135097/ca018e2f-5058-473c-94b2-2b56d0c71e7e" width="200" height="390"/>|


|티켓 등록|주변 탐색|길찾기|
|:---:|:---:|:---:|
|<img src="https://github.com/Holiculture/Holiculture_iOS/assets/126135097/8683fc90-c300-469a-9590-9abf58bb3eae" width="200" height="390"/>|<img src="https://github.com/Holiculture/Holiculture_iOS/assets/126135097/c9ff7dea-5b8f-428a-8741-19ec02244936" width="200" height="390"/>|<img src="https://github.com/Holiculture/Holiculture_iOS/assets/126135097/e6700965-c100-4dfb-9a0d-9cb04aad0226" width="200" height="390"/>|
