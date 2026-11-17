# 백승환 | Backend Developer

> 서비스가 실제 환경에서 안정적으로 동작하는지 확인하고,  
> 데이터 흐름을 기반으로 문제를 해결하는 백엔드 개발자입니다.

Spring Boot 기반의 웹 서비스와 MSA 프로젝트를 개발했습니다.  
기능 구현에 그치지 않고 API Gateway, 비동기 이벤트 처리, 배포 환경, 부하 테스트까지 연결해 보며 서비스의 안정성을 고민합니다.

## Tech Stack

**Backend**

Java · Spring Boot · Spring Data JPA · MyBatis · Spring Cloud Gateway

**Data and Messaging**

PostgreSQL · MySQL · Redis · Kafka · Flyway

**Infrastructure**

AWS EC2 · Docker Compose · Caddy · GitHub · Git

**Frontend**

React · JavaScript · AJAX

## Featured Projects

### 매삼코 - MSA 기반 AI 학습 플랫폼

- API Gateway의 JWT 검증, 명시적 라우팅, Redis 기반 Rate Limit 적용
- AWS EC2와 Docker Compose 기반 서비스 실행 환경 구성
- Kafka 기반 비동기 채점 처리 흐름의 안정성 검증
- JMeter 3,000건 요청 테스트에서 채점 오류율을 **4.53%에서 0%로 개선**
- 사용자·문제 조합의 동시 제출 경합을 PostgreSQL advisory lock으로 제어

[Repository](https://github.com/maesamco/maesamco-backend) · [Portfolio](https://drive.google.com/file/d/12MDNujSFlOT503GsPhIDmRCGuCYiQspc/view) · 
[프로젝트 브로셔](https://app.notion.com/p/3-6bfae7ef38128340a34e815ed6e6fba9)

### 돌보미 - React 기반 간병인 매칭 서비스

- 조건 검색과 건강일지 CRUD 기능 구현
- S3 Multipart Upload 기반 파일 업로드 기능 구현
- React 화면과 Spring Boot API 연동

[Repository](https://github.com/Hwan100/Dolbomi) · [Portfolio](https://drive.google.com/file/d/1U0E0yxRwlMNEKx55p7Ofthei_IdBghAU/view)

### 출결관리 ERP 시스템

- 관리자·강사·수강생 권한에 따른 출결, 강의, 수강생 관리 기능 구현
- MyBatis와 SQL JOIN 기반 데이터 조회 구현
- 세션 기반 로그인과 역할별 접근 제어 적용
- AJAX와 JSON 응답을 활용해 화면 일부를 비동기로 갱신

[Repository](https://github.com/Hwan100/semi)

## What I Value

- 동시 요청에서도 데이터 정합성을 지키는 설계
- 로그와 지표를 바탕으로 원인을 확인하는 문제 해결
- 개발 전 화면 흐름과 API 계약을 팀과 명확히 맞추는 협업
- 사용 환경과 배포 이후까지 고려하는 구현

## Contact

- Email: tmdghks605@naver.com
