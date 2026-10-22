# 이태랑 (Tailang Lee)

**소프트웨어 아키텍트 | 백엔드, 풀스택 엔지니어**

6년간 요구사항 정의부터 설계, 개발, 운영까지 맡아 왔습니다.
일본에서 자랐고, 일본 고객사의 B2B SaaS 프로젝트를 상담과 제안 단계부터 직접 맡아 왔습니다.
최근에는 Upstage Embed 2와 Solar Pro로 약 65만 건의 데이터를 검색하고 답변하는 RAG를 만들고 평가했습니다.

[Portfolio](https://blosseden.com/ko) | [Email](mailto:sua0326@gmail.com)

---

## 기술

**Language**

<img src="https://skillicons.dev/icons?i=ts,java,kotlin,py" />

**Backend**

<img src="https://skillicons.dev/icons?i=nestjs,spring,django" />

**Data**

<img src="https://skillicons.dev/icons?i=postgres,mysql,redis,kafka" />

**Infra**

<img src="https://skillicons.dev/icons?i=aws,gcp,docker,linux,githubactions,jenkins,grafana,prometheus" />

**Frontend**

<img src="https://skillicons.dev/icons?i=react,nextjs" />

**AI**

![Upstage Embed 2](https://img.shields.io/badge/Upstage-Embed%202-6B4EFF?style=for-the-badge)
![Upstage Solar Pro](https://img.shields.io/badge/Upstage-Solar%20Pro-6B4EFF?style=for-the-badge)
![pgvector](https://img.shields.io/badge/pgvector-Vector%20Search-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude%20Code-D97757?style=for-the-badge&logo=anthropic&logoColor=white)

---

## 주요 작업

### RAG 구현과 평가 (Visual Art Communication Agency 추가 프로젝트, 2026)
- 방송 공지 약 65만 건을 Upstage Embed 2로 임베딩해 PostgreSQL pgvector에 저장
- Solar Pro가 근거 공지를 인용해 답변하는 구조를, 별도 RAG 프레임워크 없이 API로 직접 연결
- 평가용 질문 세트로 검색 순위와 답변의 근거 인용을 확인해 품질을 평가

### 생방송 데이터 분석 플랫폼 (1인 설계, 개발, 운영)
- 생방송의 채팅, 후원, 입퇴장 이벤트를 실시간으로 수집하고 분석
- Redis 리스(lease)로 방송마다 담당 수집 서버를 정해 중복 수집을 줄임
- 장애 시 직전 유효값을 복원해 지표가 끊기지 않게 하고, 고액 후원은 1초 이내에 감지해 알림

### 일본 B2B SaaS (Digicore-Lab, 테크니컬 매니저)
- 일본 고객사의 요구를 상담과 제안 단계부터 직접 파악하고, 요구사항 정의와 기술 설계를 담당
- 고객 기업끼리 데이터가 섞이지 않는 멀티테넌트 구조를 설계, 구현

### 화장품 자사몰 성능 개선
- 쿼리와 캐시 최적화로 메인 화면 로딩 2.9초 → 0.51초, 리뷰 조회 1.9초 → 0.211초

---

## 언어
한국어, 일본어 (모국어 수준) | 영어 (읽기 가능, 회화는 기초) | 중국어 (HSK 5급)
