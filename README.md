# NasRun 연동 가이드

NasRun SDK는 실행형/미션형 광고를 진행하기 위한 SDK 입니다.

`Android`와 `iOS` 플렛폼을 지원합니다.

플렛폼 별 사이트로 이동하여 SDK 및 예제 소스를 다운받을 수 있습니다.

- [Android SDK](https://github.com/mafin-global/nas-run-android)
- [iOS SDK](https://github.com/mafin-global/nas-run-ios)


## Android 연동 가이드
- [1. 개요](https://github.com/mafin-global/nas-run-android#1-개요)
- [2. 설치](https://github.com/mafin-global/nas-run-android#2-설치)
  - [2-1. SDK 파일 추가](https://github.com/mafin-global/nas-run-android#2-1-sdk-파일-추가)
  - [2-2. 의존성 추가](https://github.com/mafin-global/nas-run-android#2-2-의존성-추가)
  - [2-3. 권한 추가](https://github.com/mafin-global/nas-run-android#2-3-권한-추가)
  - [2-4. Proguard 예외 처리](https://github.com/mafin-global/nas-run-android#2-4-Proguard-예외-처리)
- [3. SDK 사용](https://github.com/mafin-global/nas-run-android#3-sdk-사용)
  - [3-1. SDK 호출](https://github.com/mafin-global/nas-run-android#3-1-sdk-호출)
  - [3-2. 호출 시점](https://github.com/mafin-global/nas-run-android#3-2-호출-시점)
- [4. 연동 확인](https://github.com/mafin-global/nas-run-android#4-연동-확인)

## iOS 연동 가이드
- [1. 개요](https://github.com/mafin-global/nas-run-ios#1-개요)
- [2. 설치](https://github.com/mafin-global/nas-run-ios#2-설치)
  - [2-1. SDK 파일 추가](https://github.com/mafin-global/nas-run-ios#2-1-sdk-파일-추가)
  - [2-2. 라이브러리 추가](https://github.com/mafin-global/nas-run-ios#2-2-라이브러리-추가)
  - [2-3. 추적 권한 허용 표시 문구 설정](https://github.com/mafin-global/nas-run-ios#2-3-추적-권한-허용-표시-문구-설정)
  - [2-4. Privacy Manifest 설정](https://github.com/mafin-global/nas-run-ios#2-4-privacy-manifest-설정)
- [3. SDK 사용](https://github.com/mafin-global/nas-run-ios#3-sdk-사용)
  - [3-1. SDK 호출](https://github.com/mafin-global/nas-run-ios#3-1-sdk-호출)
  - [3-2. 호출 시점](https://github.com/mafin-global/nas-run-ios#3-2-호출-시점)
- [4. 연동 확인](https://github.com/mafin-global/nas-run-ios#4-연동-확인)
