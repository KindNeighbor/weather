# weather
- 하루의 날씨와 일기를 기록하는 서비스 프로젝트
- stack : Spring boot, JPA, Mysql, swagger

## 구현된 기능
- 매일 새벽 1시에 날씨 데이터를 외부 API(Open Weather Map)에서 받아 DB에 저장
- DB와 관련된 함수들을 트랜잭션 처리
- logback 을 이용하여 프로젝트에 로그를 남기기
- ExceptionHandler 을 이용한 예외처리
- swagger 을 이용하여 API documentation 생성
