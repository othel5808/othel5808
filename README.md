 
[![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=othel5808&show_icons=true)](https://github.com/othel5808/github-readme-stats)
# 💬Tech Skill
![Python](https://img.shields.io/badge/Python-3776AB?style=square&logo=Python&logoColor=white)
![C/C++](https://img.shields.io/badge/C++-00427E?style=square&logo=C%2B%2B&logoColor=white)
![R](https://img.shields.io/badge/R-5d6164?style=square&logo=R&logoColor=white)
![Java](https://img.shields.io/badge/Java-E51F24?style=square&logo=Java&logoColor=white)

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-305D8D?style=square&logo=PostgreSQL&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-DD8A00?style=square&logo=MySQL&logoColor=white)

---

## About me
백엔드와 데이터 엔지니어 그레이 영역에서 최적의 해답을 탐험하는 개발자.
자칭 얼리어답터
---
## Work Experiences

### 밀리의 서재 (2021.11 ~ 2026.01)

- 인프라팀 (2021.11 ~ 2022.03)
- 서비스개발팀/DX개발팀 (2022.04 ~ 2026.01, 팀명 변경)

#### 기술 스택

##### Language / Framework

- Python, Django, FastAPI
- PHP, CodeIgniter
- Kotlin 1.9, Spring Boot 3.2

##### Database

- MySQL, PostgreSQL, PrestoSQL

##### Infra / DevOps

- Docker, Kubernetes, Jenkins
- Airflow, Prefect, Supervisor
- Kafka, etc.

##### Cloud / Data

- AWS OpenSearch, AWS Athena, AWS DMS
- Apache Superset

---

## Work Experiences

### 밀리의 서재 (2021.11 ~ 2026.01)

- 인프라팀 (2021.11 ~ 2022.03)
- 서비스개발팀/DX개발팀 (2022.04 ~ 2026.01, 팀명 변경)

#### 기술 스택

##### Language / Framework

- Python, Django, FastAPI
- PHP, CodeIgniter
- Kotlin 1.9, Spring Boot 3.2

##### Database

- MySQL, PostgreSQL, PrestoSQL

##### Infra / DevOps

- Docker, Kubernetes, Jenkins
- Airflow, Prefect, Supervisor
- Kafka

##### Cloud / Data

- AWS OpenSearch, AWS Athena, AWS DMS
- Apache Superset

---

#### PG 정산 내역 연동 배치 구성

- Self-hosted Prefect 기반 배치 서버 PoC 수행
    - Azure AD OAuth 2.0 인증 플로우 개발
- Supervisor 기반 Python Script 레거시 배치를 Spring Batch로 현대화
    - 안정적인 정산 파이프라인 및 데이터 정합성 검증 체계 강화
    - Google Play / Apple App Store 매출 내역 수집 및 정산 배치 파이프라인 구성
    - 카카오페이, 이니시스 모빌리언스, 네이버페이 등 PG사 및 AppStore별 정산 데이터 적재를 위한 DB 스키마 설계
    - 일 단위 스케줄링을 통한 매출 데이터 자동 수집
    - PG사 및 AppStore 정산 금액 정합성 검증 로직 구현

#### 신 카테고리 도입을 위한 배치 개선 및 데이터 마이그레이션

- 기존 도서 분류 체계와 독립적인 신규 카테고리 도입을 위한 배치 파이프라인 설계
- 랭킹 및 검색 기능 지원을 위한 대규모 데이터 마이그레이션 수행
- Airflow DAG 분석 및 의존성 분리를 통한 영향 범위 최소화
    - 랭킹 랭킹 연산 쿼리 최적화 및 인덱스 재설계를 통해 배치 성능 8배 개선 (120분 → 15분)
    - DB Deadlock 이슈로 인한 랭킹 배치 실패 원인 분석 및 DAG 재설계

#### 주간 서비스 성능 지표 모니터링 배치 구성

- AWS WAF 로그 및 CloudWatch Metrics를 활용한 HTTP 응답 코드 분포 및 DB Slow Query 수집/분석
- 집계 결과를 주간 단위로 Slack Webhook을 통해 자동 발송하는 알림 파이프라인 구성

#### 밀리 플레이스 신규 기능 개발

- 제휴 카페 할인 서비스를 위한 외부 연동 API 및 CMS 관리 페이지 설계/개발
- 서비스 요구사항 기반 DB 스키마 설계
- 프로젝트 백엔드 담당자로서 아래 역할 수행
    - 유관 부서 간 요구사항 조율 및 일정 협의
    - CMS UI 구성 요소 정의 및 기능 확장 개발

#### 포스트 검색 기능 개발

- AWS OpenSearch를 활용한 포스트 전문 검색(Full-Text Search) 기능 설계 및 개발
- 은전한닢(seunjeon) 형태소 분석기 기반 밀리 도메인 특화 Custom Analyzer 구성
    - 도메인 톡화 사전을 통한 검색 정확도 개선
- 기존 포스트 데이터 인덱싱 마이그레이션 수행

#### 신규 PG 연동 및 구독권 상품 개발
- 신규 PG사(스마트로) 결제 API 연동
- 기존에 구성된 Django 결제 API  Boilerplate 패턴으로 코드 리팩토링
- 신규 PG사 적용에 따른 레거시 결제 API 수정
- PG 추가에 따른 프로모션 구독권 상품 관련 API 개발

#### 사용자 활동 데이터 수집 파이프라인 구성

- FastAPI 이벤트 수집 서버와 AWS Kinesis Data Firehose를 연동한 실시간 사용자 행동 데이터 수집 파이프라인 구축
- S3 적재 데이터를 AWS Athena로 쿼리하여 사용자 활동 지표 집계 및 내부 분석 환경 구성

#### 회원 지표 체계 수립

- 기존 회원/구독 지표의 정의 불일치 및 데이터 오류 식별 후 지표 재정립
- 회원 유형(B2C, 제휴, B2B) 및 구독 상태(해지자 재구독, 연속 재구독 등) 분류 체계 재정의
- AWS DMS 기반 ELT 파이프라인 구성 및 Athena를 활용한 대용량 데이터 분석 환경 구축
- IR 대응을 위한 공식 데이터 기준 수립
- Apache Superset 기반 BI 대시보드 구축 및 시각화 환경 이전
    - 서비스 DB에 직접 연결되어 운영 부하를 유발하던 Redash를 Deprecated

#### 회계 감사 대응 지원

- 감사 요건에 따른 데이터 추출 쿼리 작성 및 증빙 자료 산출

---

### 주식회사 스프링클라우드 (2020.06. ~ 2021.07.)

- 백엔드팀 (2020.06. ~ 2021.07.)

자율주행 자동차 운영 서비스를 제공하는 스타트업의 초기 멤버로 합류하여 백엔드 업무를 수행

- Django 기반 API 개발
- 차량 데이터 연동 및 관리를 위한 Kafka 환경 구성 및 유지보수
    - NiFi를 통한 데이터 플로우 관리
- Navya 등의 자율주행 셔틀과 연동 및 서비스를 위한 api 개발
#### 온리원 고군산

- WebSocket을 이용한 실시간 티켓팅 및 예약 시스템 개발
    - 차량의 예상 도착 시간(ETA) 및 근거리 차량 우선 예약 로직 개발
    - 기상청 RSS 연동
    - 차량 위치 표시를 위한 Tracking 데이터 파이프라인 구성

#### 우정사업본부 협동 과제

- 우정사업본부(우체국 앱) 내 Push API 연동
- DB 스키마 및 쿼리 설계

---

## Education

- 2020.02. 강릉원주대학교 컴퓨터공학과 석사 졸업
    - 연구주제 : 변전소 고장 복구 지원 전문가 시스템 구축
    - 핵심 요약 : 변전소 고장 시, 지원을 위한 전문가 시스템 구축에 대한 연구
- 2019.05. 정보처리기사 취득
- 2017.02. 강릉원주대학교 컴퓨터공학과 학사 졸업
