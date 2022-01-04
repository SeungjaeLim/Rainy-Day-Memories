
# 비 오는 날, 추억 한 꼬집 by 강준서, 임승재
> 갑자기 내리는 비를 소중한 추억으로
<img src="https://user-images.githubusercontent.com/74184274/148008895-5a1ff8ec-9dfa-4667-abbe-2a9ec57b6edf.png" width="300" height="300">

|오늘|연락처|추억|
|--|--|--|
|<img src="https://user-images.githubusercontent.com/74184274/148011164-2d5610b6-35ff-4d28-90e7-2ffe5bcf2859.jpg" width="225" height="400">|<img src="https://.jpg" width="190" height="400">|<img src = "https://user-images.githubusercontent.com/74184274/148010914-d404b7ce-ea9a-4edd-b6e2-18a01a7dce90.jpg" width = "225" height = "400">|

##  Splash
> 비 오는 날, 감성을 자극하는 인트로

  <img src="https://user-images.githubusercontent.com/74184274/148010894-8befce8b-a87e-42d1-b559-25e87e663ad4.jpg" width="225" height="400">
  
   - `SplashActivity.java`에서 `LottieAnimationView`를 이용하여 After Effect 애니메이션을 랜더링하여 `loading.json`을 보여줍니다.

##  Main
> 다양한 기능을 편하게 사용하기 위해 만든 스와이프 가능한 탭 구조

  <img src="." width="225" height="400">
  
   - `MainActivity.java`에서 `ViewPager`에 `TabLayout`을 적용하여 스와이프 가능한 탭 구조로 `Fragment`를 보여줍니다.

##  Tab1 : 오늘
> "나 지금 N1이야, 비오는데 데리러 와 줄 수 있어?" 

- ### 현 위치, 오늘 기온과 날씨
  
  <img src="https://user-images.githubusercontent.com/74184274/148011164-2d5610b6-35ff-4d28-90e7-2ffe5bcf2859.jpg" width="225" height="400"> 
  
  - 비오는 날 처음 보는 장소, 친구가 데리러 올 수 있는 장소를 지도에서 확인할 수 있습니다.
  - 날씨 확인을 통해 나가기 10분 전, 미리 데리러 오도록 연락할 수 있습니다.
  - 기온 확인을 통해 데리러 오는 친구에게 "오늘 춥다, 따뜻하게 입고 나와" 한마디 건네는건 어떨까요?
  
      - Google Maps API의 `MapView`를 이용해 지도를 보여줍니다.
      - `getLastLocation()`를 통해 현재 위치를 받아오고, 이를 지도에 표시합니다.
      - Geocoder를 이용하여 위도, 경도 값을 바탕으로 역지오코딩해 도시의 이름을 저장합니다.
      - OpenWeatherMap API에 역지오코딩 값을 이용해 현 위치의 날씨와 기온을 `json`으로 받아와 나타냅니다. 

## Tab2 : !
> !
> !
- ### !
  <img src = "https://.jpg" width = "190" height = "400" >
  
  - !
  - !
  - !
  - !
  - !

## Tab3 : 추억
> 비오는 날의 기억을 간직하고 싶은 추억으로 남기세요

<br />

- ### 사계절 앨범
  <img src = "https://.jpg" width = "190" height = "400">

  - !
  - !
  - !

- ### 초기 화면
  <img src = "!.jpg" width="190" height="400">

  - !

