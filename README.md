<div align="center">

# 김응석 | Data & Software Engineer

수학적 사고를 바탕으로 데이터를 분석하고, 모델과 서비스를 실제로 동작하는 형태까지 구현합니다.

</div>

## About Me

- 수학 전공, 데이터 분석·개발 교육 1,312시간 이수
- 데이터 전처리·모델링부터 백엔드 API, 프론트엔드, 배포 환경까지 프로젝트 경험
- 모든 팀 프로젝트를 Git 기반으로 진행하며 협업 및 버전 관리 경험 보유
- SQLD · 정보처리기사 · 빅데이터분석기사

## Tech Stack

| Area | Skills |
|---|---|
| Data & ML | Python, pandas, NumPy, scikit-learn, RandomForest, FastAPI |
| Backend | Java, Spring MVC, MyBatis, REST API, Oracle, PostgreSQL |
| Frontend | React, JavaScript, HTML, CSS, Bootstrap, JSP |
| Infra & Collaboration | Git, GitHub, Docker, Kubernetes, GitHub Actions |

## Featured Projects

### [LocalQuest](https://github.com/Eung-Seok/LocalQuest)

지역 상권과 사용자를 연결하는 위치 기반 퀘스트·리워드 플랫폼입니다.

- **구성:** React 프론트엔드 + Spring MVC/JSP 백엔드
- **기술:** Java 11, Spring MVC, MyBatis, Oracle, React, Redux Toolkit, JWT, QR
- **주요 기능:** 퀘스트 수행, QR 인증, 포인트·보상, 랭킹, 사업자·관리자 기능
- **담당 작업:** 관리자 공지사항 CRUD, 사업자 문의·매장 관리 기능 및 화면 연동

### [HPDFS](https://github.com/Eung-Seok/HPDFS)

HDD/SSD의 SMART 데이터를 이용해 저장장치 고장을 사전에 예측하고 모니터링하는 시스템입니다.

- **모델:** Backblaze 데이터 기반 RandomForest, 임계값 0.36
- **성능:** Accuracy 97.22%, Failure Recall 85.40%, F2-score 85.59%, ROC-AUC 96.80%
- **v1:** Windows 포터블 EXE, 로컬 예측 및 Streamlit 대시보드
- **v2:** FastAPI · PostgreSQL · Streamlit · Docker Compose · Kubernetes · GitHub Actions

### [undefined](https://github.com/Eung-Seok/undefined)

조직의 프로젝트, 업무, 일정과 게시판을 한곳에서 관리하는 협업 시스템입니다.

- **기술:** Java 11, Spring MVC, MyBatis, Oracle, JSP
- **주요 기능:** 프로젝트·업무·이슈 관리, 부서 구조, 알림, 게시판, 대시보드
- **외부 연동:** Google Calendar API를 통한 일정 관리

### [OpenPlace](https://github.com/Eung-Seok/openplace)

시민이 지역의 공공시설 개선안을 제안하고 참여하는 시민 기반 펀딩 플랫폼입니다.

- **기술:** React, React Router, Bootstrap, Styled Components, GitHub Pages
- **주요 기능:** 펀딩 프로젝트 탐색·상세 조회, 커뮤니티, 검색, 회원정보 및 결제 UI
- **핵심 경험:** 컴포넌트 기반 UI 설계와 사용자 흐름 구현

## Research

### Korean Dialect ASR Post-processing

Whisper의 경상도 방언 인식 결과를 의미를 보존한 표준어로 변환하는 후보 기반 후처리 파이프라인을 연구했습니다.

- Whisper 1-best → 후보 탐지·생성 → KoELECTRA-small-v3 선택기
- 공정 비교 평가 7,427문장
- WER **37.98% → 34.36%**, CER **18.68% → 17.37%**
- FT GPT-4o mini 대비 과도한 변경(changed_count ≥ 11) **270건 → 7건**
- SPECOM 2026: *A Corpus-Based Approach to Candidate Generation for Korean Dialect ASR Post-Processing*

## Learning Repositories

아래 저장소는 교육 과정에서 수업을 따라가며 작성한 실습 코드입니다.

- [be_study](https://github.com/Eung-Seok/be_study) — 백엔드 기초 실습
- [fe_study](https://github.com/Eung-Seok/fe_study) — 프론트엔드 기초 실습
- [fe_react_study](https://github.com/Eung-Seok/fe_react_study) — React 실습
- [spring_study](https://github.com/Eung-Seok/spring_study) — Spring 실습
- [database_study](https://github.com/Eung-Seok/database_study) — SQL·데이터베이스 실습
- [docker_study](https://github.com/Eung-Seok/docker_study) — Docker 실습
- [bigdata_study](https://github.com/Eung-Seok/bigdata_study) — 빅데이터 분석 실습
