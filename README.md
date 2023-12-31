
# C# Basic
## C# 기본문법 ~ 응용 앱 개발

- [Basic C# Portfolio](https://github.com/LaniJeong/basic-CSharp-2023#readme)
  - Winform 샤용한 책 대여 앱 만들기

<br />

- [WPF Portfolio](https://github.com/LaniJeong/pknu-wpf-2023)
  - MVVM패턴 사용하여 영화검색 앱 만들기
  - DB바인딩 하여 미세먼지 앱 만들기
<br/>

# Team Project: Smart Building Project
## WPF로 관리자용, 거주자용 앱 제작
### 목적
#### - 관리자용 앱을 통해 센서를 직접 제어하고 빌딩 전체의 위험요소와 주차장을 관리하여 거주자들의 편리성을 증대시킨다.
#### - 거주자용 앱을 사용하여 집 내부의 상황을 외부에서도 조정 할 수 있도록 하여 삶의 질을 향상시킨다.

<br/>

#### <건물 관리자용 모니터 앱>
<img src="https://raw.githubusercontent.com/LaniJeong/study_CSharp/main/smartbuilding_app.png" width="700">

#### <거주자용 모니터 앱>
<img src="https://raw.githubusercontent.com/LaniJeong/study_CSharp/main/smarthome_app.png" width="700">

<br/>

### 1일차(7.6)
- WPF 템플릿 제작
- 차량 관리 화면(진행 중)
### 2일차(7.7)
- 차량 관리 화면 완료
	- 차량 등록, 수정, 삭제 => MySQL DB 바인딩 완료
- 로그인 화면 완료
	- MySQL 관리자 DB 바인딩 완료
	- 앱 구현 마지막 단계에서 로드 이벤트 추가 예정
### 3일차(7.11)
- 센서 제어 대시보드 정리(진행 중)
- 날씨 화면 제작(진행 중)

### 4일차(7.12)
- 날씨 화면 제작(진행 중)
	- 기상청 API 연동 완료
	- 온도, 습도, 풍속 textblock에 바인딩 완료

### 5일차 (7.13)
- 날씨 화면 제작(진행 중)
	- 기상청 API 연동 완료
	- 온도, 습도, 풍속 textblock에 바인딩 완료
	- 값에 따른 날씨 이미지 변경 완료
	- 추가 진행사항 : 대시보드 정리

### 7일차 (7.15)
- 아두이노 <- 시리얼 통신 -> 라즈베리파이 <- MQTT -> WPF 앱 확인 완료
	- WPF 앱에서 토글버튼으로 아두이노에 연결된 LED 제어 가능

### 6일차 (7.14)
- 현재 단계에서 필요한 화면은 구현 완료
	- 라즈베리파이 <-> 아두이노 시리얼 통신 완료 
	- 라즈베리파이 <-> 윈도우(WPF 앱) MQTT 통신 확인 필요
	- 통신 완료시 나머지 화면 제작

### 8일차 (7.16)
- Timer 사용 -> 실행 중 현재 시간 실시간으로 바뀜
- 추가 작업은 센서 및 기능 구현 내용 정리 후 필요

### 9일차 (7.17)
- 기상청 홈페이지 크롤링 테스트
	- 기존 API 오류 잦아 홈페이지 크롤링 테스트
	- string으로 받아오는 값 double 형식으로 변환해야하는데 오류남... 확인 필요

### 10일차 (7.18)
- 기상청 홈페이지 크롤링 완료
	- 기상청 API 대신 웹크롤링해서 받아온 값으로 날씨영역 바인딩
- 대시보드 정리

### 11일차 (7.24)
- 사용자용 모니터링 앱 정리 진행 중
- MQTT 통신 테스트
  - 토글 버튼으로 LED 단순 제어 가능

### 12일차 (7.25)
- 사용자용 모니터링 앱 정리 진행 중
  - 온습도 센서 화면 구현 완료

### 13일차 (7.28)
- 사용자용 모니터링 앱 정리
- MQTT 통신
  - 온습도값 바인딩
  - LED 제어 가능

### 14일차 (7.31)
- 관리자용 모니터링 앱
- MQTT 통신
  - 차양막 버튼 추가
  - LED 전체소등 버튼 추가

### 15일차 (8.2)
- 사용자용 모니터 앱
  - ui수정
  - 엘리베이터 호출 버튼 추가
 
### 16일차 (8.4)
- 사용자용 모니터 앱
  - MQTT통신 연결 확인 섹션
- 입차현황 view
  - 삭제버튼 활성화(DB 연동)

### 17일차 (8.8)
- 관리자용 모니터 앱
  - MQTT통신 연결 확인 섹션 수정
- 날씨 웹크롤링 오류 수정
  - Timespan 조정
 
<!--# study_C#
 초보자를 위한 C# 200제

 - 1일차
     - Part 1: 간단한 C#프로그램을 명령줄에서 컴파일하기
        - 001~005

 - 2일차
     - Part 1: 간단한 C#프로그램을 명령줄에서 컴파일하기
         - 006~010
-->
