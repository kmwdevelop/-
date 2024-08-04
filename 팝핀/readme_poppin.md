# [프로젝트] 팝업스토어 앱 - Poppin (2024.06 ~ 2024.07 / 2개월)

## **팝핀이란?**

#### 팝업스토어의 소식을 알림 받고, 정보를 제공받는 서비스 입니다.

<img src="팝핀/poppin_store.png" width=500/>

### 개발한 기능 2가지

### 1. 커스텀 캘린더

<img src="팝핀/calendar02.PNG" width=300/>&nbsp;
<img src="팝핀/calendarFull.PNG" width=300/>

- react-native-calendar 라이브러리를 커스텀(색상, 모양 등) 합니다.
- 해당 날짜의 팝업스토어를 BottomSheet 로 보여줍니다.
- BottomSheet 를 내리면, 전체화면 캘린더가 나타나도록 합니다.
#### 사용한 기술
1. [react-native-calendar](https://www.npmjs.com/package/react-native-calendars) 라이브러리 사용
2. [react-native-bottomsheet-navigation](https://www.npmjs.com/package/react-native-bottomsheet-navigation) 라이브러리 사용
3. 커스텀 훅 사용

#### 성과
- 구현하기 까다로운 캘린더를 구현해보고, 캘린더의 기능과 매커니즘을 이해할 수 있었다.
    

### 2. 알람
<img src="팝핀/alarmListNon.png" width=300/>&nbsp;
<img src="팝핀/alarmList.png" width=300/>&nbsp;
<img src="팝핀/alarmSettingOn.png" width=300/>&nbsp;
<img src="팝핀/alarmNoti.PNG" width=300/>&nbsp;

- 파이어베이스 알람 서비스와 연동합니다.
- FCM Token을 받아와 앱서버에 등록하여 관리합니다.
- 각종 알람 설정을 할 수 있습니다.
#### 사용한 기술
1. [react-native-firebase/messaging](https://www.npmjs.com/package/@react-native-firebase/messaging) 라이브러리 사용
2. 커스텀 훅 사용
    
#### 성과
- 파이어베이스의 알람 기능을 자세히 경험할 수 있었다.
- APNS의 개념에 대해서 정리할 수 있었다.
- CSR, CER 인증서 Provisioning Profile, 푸시키 등에 대해 정리할 수 있었다. [블로그 정리 글](https://velog.io/@unknown420/iOS-%EC%9D%B8%EC%A6%9D%EC%84%9C-%EA%B0%80%EC%9D%B4%EB%93%9C-1%ED%83%84-CSR-%EC%8B%A0%EC%B2%AD%EC%84%9C%EC%99%80-CER-%EC%9D%B8%EC%A6%9D%EC%84%9C)
