HelloExpo 201740220 성형주
=============
HelloExpo 프로젝트
-------------
## 05.28
> React-native CLI의 특징
```
- RN개발진들이 운영하고 있어서 업데이트가 빠름
- native 언어인 java, kotln과 swift를 사용 가능
- 안드로이드는 Android studio, ios는 Xcode가 있어야 함
```
>Expo의 특징
```
- 쉬운 build system
- Android studio, Xcode 없이도 Expo SDK를 이용해 빌드 및 테스트가 가능
- expo 앱을 이용하면 자신의 스마트폰에서 직접 결과 확인이 가능
- MacBook 없이도 ios 환경도 빌드가 가능
- 카메라, 위치, 알림, 센서 등에 접근할 수 있는 라이브러리가 존재
- 언제든지 React-Native-CLI로 변환이 가능
- 상대적으로 업데이트가 느림
- native 환경에서 사용하는 third party 라이브러리를 사용할 수 없다는 한계 존재
```
### Expo CLI 설치
```
- npm install -g expo-cli
- expo --version(설치 버전 확인)
```
### HelloExpo 프로젝트 생성
```
- expo init HelloExpo
- 템플릿을 선택하는 화면에서 blank를 선택
```
### 프로젝트 실행
```
- expo start
- 실행 후 w 클릭 시 웹에서도 동작 확인 가능
```
### MaterialBottomTabNavigator 라이브러리 추가
```
- npm install @react-navigation/material-bottom-tabs react-native-paper
```
### 스마트폰을 통한 실행 확인
```
- expo 앱 설치 후 QR코드를 통해 자신의 폰에서도 동작 확인 가능
- 코드 수정 시 실시간으로 변경
```