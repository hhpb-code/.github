# 항해플러스 백엔드코스 6기 Java/Spring Boot 기반 백엔드 학습 공간 (HHPB-Code)

안녕하세요! 👋  
이곳은 항해플러스 백엔드코스 6기를 수강하면서 Java와 Spring Boot를 활용하여 백엔드 개발의 전반적인 과정을 학습하고 프로젝트를 진행하는 개인 작업 공간입니다.

## 소개

HHPB-Code는 Java와 Spring Boot를 기반으로 백엔드 개발의 다양한 측면을 탐구하고 실제 애플리케이션을 구현하는 과정을 담고 있습니다.

## 학습 목표

- 백엔드 아키텍처 설계 및 구현 능력 개발
- TDD(Test-Driven Development) 방법론을 활용한 테스트 코드 작성 능력 향상
- clean code 작성 및 리팩토링 능력 향상
- 대용량 트래픽과 데이터 처리를 고려한 시스템 설계 능력 향상
- 장애 대응 및 모니터링 능력 향상

## 기술 스택

- 주요 언어 및 프레임워크: Java, Spring Boot
- 데이터베이스: MySQL, JPA/Hibernate
- 테스팅: JUnit, Mockito
- 빌드 도구: Gradle
- 버전 관리: Git, GitHub
- 클라우드: AWS

## 커리큘럼

- 1주차: TDD 로 개발하기 (TDD)
  - [hhplus-tdd-java](https://github.com/hhpb-code/hhplus-tdd-java/pulls?q=is:pr+is:closed)
  - [README.md](https://github.com/hhpb-code/hhplus-tdd-java/blob/master/README.md)
- 2주차: 특강 신청 서비스 개발하기 (Clean Architecture, TDD)
  - [hhplus-tdd-clean-architecture-java](https://github.com/hhpb-code/hhplus-tdd-clean-architecture-java/pulls?q=is%3Apr+is%3Aclosed)
- 3주차: 콘서트 예약 서비스 설계하기
  - [프로젝트 Milestone 작성 및 요구사항 분석](https://github.com/hhpb-code/hhplus-concert/pull/1)
  - [프로젝트 ERD, API 명세서, Mock API 구현](https://github.com/hhpb-code/hhplus-concert/pull/2)
- 4주차: 콘서트 예약 서비스 비지니스 구현하기
  - [비지니스 구현 및 Swagger 작성](https://github.com/hhpb-code/hhplus-concert/pulls?q=is:pr+is:closed+label:step7)
  - [비즈니스 Usecase 개발 및 통합 테스트 작성](https://github.com/hhpb-code/hhplus-concert/pull/18)
- 5주차: 콘서트 예약 서비스 에러 핸들링 및 Filter나 Interceptor을 활용한 기능 관점 분리하기
  - [글로벌 에러 핸들러, 토큰 검증 인터셉터 등록](https://github.com/hhpb-code/hhplus-concert/pull/24)
  - [시나리오별 동시성 통합 테스트 작성 및 회고](https://github.com/hhpb-code/hhplus-concert/pull/26)
- 6주차: 콘서트 예약 서비스의 동시성 제어하기
  - [콘서트 시나리오 동시성 이슈 분석](https://github.com/hhpb-code/hhplus-concert/pull/28)
  - [동시성 제어 고도화 (비관적락, 낙관적락, 분산락)](https://github.com/hhpb-code/hhplus-concert/pull/29)
- 7주차: 콘서트 예약 서비스의 캐시와 Redis를 활용한 성능 개선하기
  - [쿼리 캐싱 혹은 Redis 를 이용한 로직 이관을 통해 성능 개선 보고서](https://github.com/hhpb-code/hhplus-concert/pull/31)
  - [콘서트 예약 시나리오 대기열 개선 RDBMS -> Redis](https://github.com/hhpb-code/hhplus-concert/pull/32)
- 8주차: 콘서트 예약 서비스의 인덱스와 부가기능 추가하기
  - [인덱스 추가 및 보고서 작성](https://github.com/hhpb-code/hhplus-concert/pull/34)
  - [MSA 관점에서 트랜잭션 관리 보고서 작성 및 예약 완료 Event 구현](https://github.com/hhpb-code/hhplus-concert/pull/36)
