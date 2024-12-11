

# 이젠솔루션 - LGU+ 멤버십 게이트웨이 API 유지보수

- Java, Spring/Strut, iBatis, Jeus, Webtob, Unix



- 로그에 생년월일 결과값이 null로 나오던 것 수정
- 승인/조회 API에 할인율 조회 추가

## 생년월일로 고객인증 성공/실패 시 로그 개선
2013.11-2013.11
생년월일로 고객인증 성공/실패 시 로그에 생년월일이 null로 나오던것을 수정

## 승인 IF 할인율 전송 추가, SQL 변경
2013.12-2014.01
승인/조회 API에 회원 등급에 따른 할인율 조회 가능하게 변경


## U+멤버십 내 패밀리몰(LG계열사 쇼핑몰) 할인 추가
2016.05-2016.06
u+멤버십 앱 공지 내 페이지 작성
공지 페이지 배너링크 URL 항목 추가
제휴사 AOS/IOS 다운로드 URL 항목 추가

# 주간보고 내용
## 날위한멤버십 개선
- U+패밀리몰 안내 페이지 경로 수정, UI규격서에 따라 UI 수정
- 배너 타입 U(URL) 추가 : 관리자 페이지 배너 관리의 등록, 수정, 조회 프로세스에 파라미터 target_url 추가, 어플 메인에 반환값 bannLinkURL 추가, target_url validation 추가 및 테스트



새 공지페이지 작성 및 
새 공지페이지의 해상도별 단말 테스트
![Capture+_2016-06-21-17-12-52.png](img/Capture%2B_2016-06-21-17-12-52.png){: width="10" height="10"}
<img src="img/Capture%2B_2016-06-21-17-12-52.png" width="50%" height="50%">
<img src="img/Capture%2B_2016-06-21-17-13-01.png" width="50%" height="50%">
<img src="img/Capture%2B_2016-06-21-17-13-07.png" width="50%" height="50%">
