# 아이폰 단축어 한영/영한 번역기

## 개요

iOS 12 에 신기능 '단축어'를 이용하여 선택된 문자나 클립보드에 복사된 문자를 네이버 파파고 번역기를 통해 번역합니다

![How to use](https://raw.githubusercontent.com/binarythink/iphone-shortcut-papago/master/assets/doc-img/howToUse.gif)


## 사전 준비

### 네이버 오픈 API 이용 신청

* [네이버 개발자 센터](https://developers.naver.com/products/nmt/) 에 접속해 **오픈 API 이용 신청** 을 합니다
* 처음 사용자는 **약관동의**, **계정정보 등록**, **애플리케이션 등록** 순서로 이루어집니다.
* 기존 사용자는 **애플리케이션 등록** 화면으로 넘어갑니다.
* **애플리케이션 등록** 화면에서 아래의 입력 항목을 작성합니다.
    * 어플리케이션 이름 : 작성규칙에 맞춰 알맞게 입력해주세요
    * 사용 API : `Papago NMT 번역` 을 선택합니다
    * 비로그인 오픈 API 서비스 환경 : `WEB 설정` 을 선택하고 `웹 서비스 URL` 을 입력합니다
* 등록을 완료하고 등록된 **애플리케이션 정보**에서 `Client ID` 와 `Client Secret` 을 설치시 질문에 정확하게 입력합니다.