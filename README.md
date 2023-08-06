<br/>

## Flutter 프로젝트에 있는 graddle 파일에 대해 알아보자

<br/>

### 00. Flutter에서 Dependency란?

- 내가 만들고자 하는 플러터앱이 케이크, 케이크 요리법이 코드, 재료들을 dependencies라고 비유할 수 있다.
- 재료가 없으면 케이크를 만들지 못하는 것처럼 dependencies 없이는 앱을 만들 수 없다
- Dependencies들은 라이브러리, 프레임워크, 모듈같은 앱의 꼭 필요한 필수요소이다. 코드 작성전 필수준비물 같은 느낌
- 플러턴에서는 이러한 dependencies를 `pupspec.yaml`파일에서 지정해준다,
- 만약 `flutter pub get` cmd 명령어가 실행되면 플러터는 dependencies의 링크를 타고와 fetch 해온다. 마치 케이크를 만들기 전에 시장가서 재료를 사오는 것처럼 말이다.
- 

### 01. Gradle 이란 무엇일까? 

- Gradle은 안드로이드 개발에 사용되는 Build system이다
- App building 의 과정과 dependencies들을 전반적으로 관리한다.
