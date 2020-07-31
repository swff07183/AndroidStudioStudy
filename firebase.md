### 안드로이드 앱에 파이어베이스(Firebase) 연결하기

Firebase 홈페이지 접속하기
<br>[https://firebase.google.com/?hl=ko](https://firebase.google.com/?hl=ko)

프로젝트 만들기
![](./img/firebase/1.png)

![](./img/firebase/2.png)

프로젝트 이름을 입력하고 버튼을 누르다 보면 프로젝트가 시작된다.
![](./img/firebase/3.png)


만든 프로젝트의 화면이 뜨면 밑의 사진처럼 안드로이드 버튼을 클릭한다.
![](./img/firebase/4.png)

Android 앱에 Firebase 추가 화면이 뜨면 내가 만든 Android 패키지 이름을 입력한다. 나머지 칸은 비워도 괜찮다.
![](./img/firebase/5.png)

`google-services.json 다운로드` 버튼을 클릭하고, 안드로이드 프로젝트 폴더의 `app` 폴더에 파일을 넣는다.
![](./img/firebase/6.png)
![](./img/firebase/7.png)


그다음 어플리케이션에 인터넷 사용권한을 부여해야 한다.
<br>`AndroidManifest.xml`에 `<uses-permission android:name="android.permission.INTERNET" />` 코드를 추가해준다.