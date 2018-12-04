# Awesome Application Factory  
<img src="../images/ic_launcher.png">   

## 1. 개인정보처리방침   
Awesome Application Factory(이하"AAF")는 영리를 목적으로 하는 법인 또는 개인 사업자가 아닙니다.   
오프소스 라이브러리를 매쉬업하여 사용자가 광고없이 무료로 편리한 애프리케이션을 사용 할 수 있도록 애플리케이션을 개발하고 배포하는 것을 목적으로 합니다.   
따라서 AAF의 애플리케이션은 사용자의 데이터 및 개인정보를 저장하기 위해 별도의 서버를 운영하지 않으며, 불필요하게 사용자의 개인정보를 취급하지도 않습니다.   
만약 사용중인 애플리케이션에 대한 백업 및 복구를 사용자가 원하는경우 사용자의 동의하에 Google의 OAuth인증을 통하여 사용자 개인의 Google Drive에 애플리케이션 데이터를 저장하고 이후 백업 요청 시 사용합니다.   
백업 데이터는 사용자가 Google Drive에서 별도로 공유설정을 진행하지 않는한 외부로 공개되지 않습니다.   

## 2. 애플리케이션에서 요청하는 권한 및 요청사유  
### 2.1. AAF-Easy Diary  
* android.permission.READ_EXTERNAL_STORAGE(저장소 읽기 권한)  
다이어리 첨부사진 및 포스트카드 저장을 위한 권한요청
* android.permission.WRITE_EXTERNAL_STORAGE(저장소 쓰기 권한)  
다이어리 첨부사진 및 포스트카드 로딩을 위한 권한요청
* android.permission.INTERNET(인터넷 접속 권한)  
GMS(Google Mobile Service) 연동을 위한 인터넷사용 권한요청
* android.permission.FOREGROUND_SERVICE(알림창을 이용한 서비스이용 권한)  
다이어리 첨부 사진 백업 및 복구시 알림창을 통한 진행상태 알림을 위한 권한요청

### 2.2. AAF-Easy Photo Map  
* android.permission.ACCESS_FINE_LOCATION  
* android.permission.ACCESS_COARSE_LOCATION  
* android.permission.ACCESS_NETWORK_STATE  
* android.permission.READ_EXTERNAL_STORAGE(저장소 읽기 권한)  
포토맵 저장을 위한 권한요청
* android.permission.WRITE_EXTERNAL_STORAGE(저장소 쓰기 권한)  
포토맵 로딩을 위한 권한요청
* android.permission.INTERNET(인터넷 접속 권한)  
GMS(Google Mobile Service) 연동을 위한 인터넷사용 권한요청
* android.permission.CAMERA(카메라 제어 권한)  
카메라 촬영을 통한 포토맵 등록시 필요한 카메라 제어 권한요청 

### 2.3. AAF-Easy Password  
* android.permission.INTERNET(인터넷 접속 권한)  
GMS(Google Mobile Service) 연동을 위한 인터넷사용 권한요청

### 2.4. 유소년 스포츠클럽 관리어플 Awesome Manager  
* android.permission.READ_EXTERNAL_STORAGE(저장소 읽기 권한)  
팀정보 및 출석정보 저장을 위한 권한요청
* android.permission.WRITE_EXTERNAL_STORAGE(저장소 쓰기 권한)  
팀정보 및 출석정보 로딩을 위한 권한요청
* android.permission.READ_CONTACTS(연락처 읽기 권한)  
팀원정보 등록을 위한 연락처 읽기 권한요청
* android.permission.SEND_SMS(SMS 전송 권한)  
출결정보 SMS 전송을 위한 권한요청

### 2.5. Memory Game Remember Miniman  
* android.permission.INTERNET(인터넷 접속 권한)  
GMS(Google Mobile Service) 연동을 위한 인터넷사용 권한요청

## 3. 애플리케이션 관련 문의 및 개선요청   
AAF에서 배포하는 애플리케이션에 대한 문의 및 개선요청 은 아래 2가지 방법으로 가능합니다.   
* 이메일을 통한 요청
hanjoongcho@gmail.com

* GitHub 이슈등록
https://github.com/AAFactory/aafactory.github.io/issues  
