# 예약 캘린더 (Reservation Calendar)

구글 앱스 스크립트로 개발한 **예약 시스템**입니다. 이 애플리케이션은 특정 요일과 시간대에 예약을 받고 관리할 수 있도록 설계되었습니다. 주로 연습실 예약과 같은 상황에서 활용할 수 있습니다.

https://script.google.com/macros/s/AKfycbyZffmWpWsy6WfT15xzKtZp_AICPHTgCEAeFJoy1Kgh3IQ0Dr0muZYmE8Rfow6L--JBDw/exec

## 기능 소개

- **예약 추가**: 사용자는 이름, 날짜, 시작 시간, 종료 시간, 상세 내용을 입력하여 예약을 추가할 수 있습니다.
- **예약 조회**: 캘린더에서 예약된 이벤트를 확인할 수 있습니다.
- **예약 삭제**: 기존 예약을 선택하여 삭제할 수 있습니다.
- **예약 가능 시간대 제한**: 화요일, 금요일은 17:00 ~ 23:00, 일요일은 10:00 ~ 17:00 사이에만 예약이 가능합니다.
- **연습실 정보 제공**: 연습실의 위치와 이용 가능 시간을 팝업으로 제공합니다.

## 사용 기술

- **Google Apps Script**: 서버 사이드 로직과 Google Calendar API 연동
- **HTML/CSS/JavaScript**: 클라이언트 사이드 UI 및 로직
- **FullCalendar.js**: 캘린더 UI 컴포넌트
- **Google Calendar API**: 예약 이벤트 관리
