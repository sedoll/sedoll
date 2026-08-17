# 📄 경력 기술서 (Career Description)

## 👤 기본 정보

- **성명:** 오세훈
- **직무:** Full Stack Developer (Java / Spring Boot)
- **Email:** donhanm12@gmail.com
- **SNS** [GitHub](https://github.com/sedoll), [Naver Blog](https://blog.naver.com/tmvmffpsej), [Velog](https://velog.io/@sedo11/posts)
- **AI 자동화 SNS** [Telegram](https://t.me/ai_stock_crypto_summary_news), [Instargram](https://www.instagram.com/ai_stock_crypto_summary_news/), [Threads](https://www.threads.com/@ai_stock_crypto_summary_news?hl=ko)

---

# 🛠 기술 스택 (Tech Skills)

## Backend
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![JPA](https://img.shields.io/badge/JPA-59666C?style=flat-square)
![MyBatis](https://img.shields.io/badge/MyBatis-000000?style=flat-square)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

## Frontend
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![Nuxt.js](https://img.shields.io/badge/Nuxt.js-00DC82?style=flat-square&logo=nuxtdotjs&logoColor=white)
![Alpine.js](https://img.shields.io/badge/Alpine.js-8BC0D0?style=flat-square&logo=alpinedotjs&logoColor=white)
![jQuery](https://img.shields.io/badge/jQuery-0769AD?style=flat-square&logo=jquery&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![FreeMarker](https://img.shields.io/badge/FreeMarker-326CAC?style=flat-square&logo=apachefreemarker&logoColor=white)
![Thymeleaf](https://img.shields.io/badge/Thymeleaf-005F0F?style=flat-square&logo=thymeleaf&logoColor=white)

## Database
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MSSQL](https://img.shields.io/badge/MSSQL-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

## DevOps & Infra
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)

## AI TOOL
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white)
![OpenAI Codex](https://img.shields.io/badge/GPT%20Codex-412991?style=flat-square&logo=openai&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Google%20Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)

---

# 🏢 경력 (Work Experience)

## 천재교육 (Chunjae Education)
**IT 운영팀 / T셀파 담당 | 2024.02 ~ 2026.02**

- Java / Spring Boot 기반 교육 플랫폼 개발 및 운영
- 프론트엔드·백엔드 기능 개발과 레거시 시스템 개선
- AI 서비스, 이벤트 플랫폼, 데이터 수집 시스템 구축 및 장애 대응

---

# 💻 실무 프로젝트 (Work Projects)

<details>
<summary><strong>📌 T셀파 동영상 플랫폼 개발</strong></summary>

- **기간:** 2025.11 ~ 2026.01
- **팀 구성:** 개발자 3명, 퍼블리셔 3명, 기획 2명, 디자이너 2명
- **역할:** 프론트엔드 개발
- **Tech:** Vue.js, Nuxt.js, C#, MSSQL

### 프로젝트 소개
학교 선생님들이 온라인 연수 및 교육 영상을 시청할 수 있도록 구축한 영상 학습 플랫폼입니다. Nuxt SSR 환경에서 초기 렌더링 안정성과 사용자 학습 흐름을 고려한 UI 개발에 참여했습니다.

### 주요 기여
- Nuxt.js 기반 영상 학습 화면 및 공통 컴포넌트 개발
- 영상 재생 상태와 학습 흐름을 고려한 UI/UX 개선
- 퍼블리셔·기획자와 협업하여 재사용 가능한 화면 구조 구성

### 핵심 문제 해결
**Hydration Mismatch로 인한 초기 화면 깜빡임 문제**
- 서버와 클라이언트의 렌더링 결과가 달라지는 브라우저 API 및 상태 관리 지점을 분리
- 클라이언트 전용 컴포넌트의 렌더링 시점을 조정하고 공통 UI 상태를 store 기준으로 정리
- 초기 로딩 및 화면 전환 시 발생하던 UI 불안정성 완화

### 성과
- 영상 기반 학습 플랫폼의 사용자 경험 개선
- Nuxt SSR 기반 서비스 개발 및 운영 경험 확보

</details>

<details>
<summary><strong>📌 T셀파 초등/중고등 이벤트 페이지 분리 및 고도화</strong></summary>

- **기간:** 2025.07 ~ 2025.10
- **팀 구성:** 개발자 1명, 퍼블리셔 2명, 기획 1명, 디자이너 1명
- **URL:** https://ele.tsherpa.co.kr/site/event-main/index.html
- **URL:** https://mh.tsherpa.co.kr/site/event-main/index.html
- **역할:** 풀스택 개발
- **Tech:** Java, Spring Boot, MyBatis, MSSQL, jQuery

### 프로젝트 소개
하나의 구조로 운영되던 이벤트 플랫폼을 초등·중고등 서비스로 분리하여 학교 급별 요구사항을 독립적으로 반영하고 유지보수성을 개선한 프로젝트입니다.

### 주요 기여
- 이벤트 시스템 URL·템플릿·데이터 구조의 도메인 분리
- 레거시 코드 리팩토링 및 공통 기능 모듈화
- 학교 급별 사용자 흐름과 UI 개선
- 단독 개발자로 백엔드와 프론트엔드 전반 담당

### 핵심 문제 해결
**단일 구조 공유로 인한 배포 충돌 및 사이드 이펙트**
- 초등·중고등 URL과 템플릿, 데이터 구조를 도메인 단위로 분리
- 공통 비즈니스 로직과 UI는 재사용 가능한 구조로 유지
- 한 서비스의 수정이 다른 서비스에 영향을 주는 구조를 개선

### 성과
- 서비스별 독립적인 기능 수정 및 배포가 가능한 구조 확보
- 이벤트 운영 및 유지보수 복잡도 감소

</details>

<details>
<summary><strong>📌 T셀파 수업 혁신 연구대회 플랫폼</strong></summary>

- **기간:** 2025.04 ~ 2025.06
- **팀 구성:** 개발자 1명, 퍼블리셔 2명, 기획 1명, 디자이너 1명
- **URL:** https://www.tsherpa.co.kr/site/gpt/index.html
- **역할:** 풀스택 개발
- **Tech:** Java, Spring Boot, JPA, MSSQL, Redis, Alpine.js

### 프로젝트 소개
교사들이 수업 아이디어를 공유하고 이벤트에 참여할 수 있도록 구축한 커뮤니티형 플랫폼으로, 신청 데이터 관리와 운영 안정성에 중점을 두고 개발했습니다.

### 주요 기여
- 아이디어 접수, 댓글, 투표 및 이벤트 신청 기능 개발
- 조회 및 신청 관련 쿼리 최적화
- 사용자 참여 흐름 중심의 UI 개선
- 단독 개발자로 서비스 기능 전반 구현

### 핵심 문제 해결
**DB와 Redis 캐시 간 데이터 불일치**
- 수정·삭제 시 DB 처리와 함께 Redis 캐시를 갱신·제거하도록 로직 개선
- 캐시 조회 우선순위와 만료 정책 점검
- 중복 신청 및 잘못된 신청 상태 노출 문제 개선

### 성과
- 이벤트 신청 데이터 정합성 및 운영 안정성 향상
- 사용자 참여 과정에서 발생하던 오류 감소

</details>

<details>
<summary><strong>📌 T셀파 AI 디지털 교과서 자료실</strong></summary>

- **기간:** 2025.01 ~ 2025.03
- **팀 구성:** 개발자 1명, 퍼블리셔 1명, 기획 1명, 디자이너 1명
- **URL:** https://ele.tsherpa.co.kr/site/aidt_data/main.html
- **역할:** 풀스택 개발
- **Tech:** Java, Spring Boot, MyBatis, MSSQL, JavaScript, FreeMarker

### 프로젝트 소개
AI 디지털 교과서 관련 자료를 카테고리별로 관리·배포하기 위한 자료 아카이빙 플랫폼입니다. 사용자 검색 기능과 관리자 자료 배포 기능을 함께 개발했습니다.

### 주요 기여
- 자료실 게시판 CRUD 및 카테고리 검색 기능 개발
- 관리자 페이지 기반 자료 등록·배포 기능 구축
- FreeMarker 기반 레거시 템플릿 구조 개선
- 단독 개발자로 사용자·관리자 기능 전반 구현

### 핵심 문제 해결
**페이지별로 파편화된 FreeMarker 템플릿 구조**
- 공통 include 경로 및 UI 영역 정리
- 반복되는 목록·상세·카테고리 구조를 공통화
- 관리자 입력값 검증 로직을 보강해 운영 중 화면 오류 위험 감소

### 성과
- 자료 관리 및 배포 프로세스 단순화
- 템플릿 유지보수 시 반복 수정 범위 축소

</details>

<details>
<summary><strong>📌 T셀파 AI 실험실</strong></summary>

- **기간:** 2024.05 ~ 2024.09
- **팀 구성:** 개발자 2명, 퍼블리셔 3명, 기획 1명, 디자이너 1명
- **URL:** https://www.tsherpa.co.kr/site/gpt/index.html
- **역할:** 풀스택 개발
- **Tech:** Java, Spring Boot, MSSQL, JavaScript, Alpine.js, OpenAI API

### 프로젝트 소개
OpenAI API를 활용해 교사와 학생이 사용할 수 있는 대화형 AI 및 독후감 첨삭 기능을 제공한 교육용 AI 플랫폼입니다.

### 주요 기여
- GPT API 기반 채팅형 AI 서비스 개발
- 사용자 입력 전처리 및 프롬프트 처리 로직 구현
- 독후감 첨삭 및 문장 개선 기능 개발
- 실시간 대화형 UI 개발

### 핵심 문제 해결
**API 응답 지연과 교육 목적에 맞지 않는 AI 응답**
- 외부 API 호출에 비동기 처리 구조를 적용해 사용자 대기 시간 개선
- 시스템 프롬프트와 사용자 입력 전처리를 강화해 AI 역할을 명확히 제한
- 영어, 반말, 목적 외 답변 등 교육 환경에 부적절한 출력 빈도 감소

### 성과
- 실제 교육 서비스에서 AI API를 연동·운영한 경험 확보
- AI 응답 품질과 사용자 경험을 함께 고려한 서비스 개발 경험 축적

</details>

<details>
<summary><strong>📌 T셀파 학교 크롤러 개발 및 운영</strong></summary>

- **기간:** 2024.02 ~ 2024.12
- **팀 구성:** 개발자 6명, 기획 1명
- **역할:** 풀스택 개발
- **Tech:** Java, Spring Boot, JPA, MyBatis, MariaDB, Selenium, Jsoup, Alpine.js

### 프로젝트 소개
전국 초·중·고등학교 홈페이지의 공지사항, 급식, 가정통신문 데이터를 자동 수집하고 공통 포맷으로 정제하는 크롤링 시스템입니다.

### 주요 기여
- 학교별 HTML 구조에 따라 동적·정적 크롤링 방식 분리
- Selenium과 Jsoup를 혼합 사용해 수집 속도와 안정성 개선
- 관리자 검수 화면 및 수집 데이터 확인 기능 개발
- 수집 실패 학교에 대한 재시도·예외 처리 로직 구현

### 핵심 문제 해결
**학교별 HTML 구조 차이와 응답 지연으로 인한 수집 실패**
- 사이트 유형별 파싱 전략을 분리하고 공통 예외 패턴을 재사용 가능하게 정리
- timeout 및 retry 기준을 적용해 일시적 접속 장애 대응
- 실패 로그와 fallback 파싱을 추가해 원인 추적 및 재처리 가능 구조 구축

### 성과
- 수작업으로 확인하던 학교 데이터 수집 자동화
- 신규 학교 사이트 대응 시간 단축
- 장애 발생 시 빠른 원인 분석과 재처리가 가능한 운영 구조 확보

</details>

---

# 🚀 개인 프로젝트 (Personal Projects)

<details>
<summary><strong>📌 AI 기반 주식/코인 뉴스 자동화 플랫폼</strong></summary>

- **Telegram:** https://t.me/osc_news
- **역할:** 1인 개발
- **Tech:** Python, FastAPI, n8n, MariaDB, Docker, Telegram API, Threads API, Gemini API, Linux

### 프로젝트 소개
주식·코인 뉴스와 YouTube 콘텐츠를 자동 수집하고 AI로 요약한 뒤 Telegram에 자동 발행하는 운영형 자동화 플랫폼입니다.

### 주요 기여
- n8n 기반 뉴스 수집·AI 요약·발행 워크플로우 설계
- YouTube 자막 자동 수집 및 AI 요약 시스템 구축
- Telegram 플랫폼 발행 구조 구현
- Docker 기반 운영 환경 구성
- 플랫폼별 발행 여부 및 성공·실패 상태를 관리하는 DB 구조 설계

### 핵심 문제 해결
**외부 API 장애와 대용량 입력으로 인한 워크플로우 불안정**
- API 요청에 retry와 timeout을 적용해 일시적 장애 시 복구 가능한 흐름 구성
- YouTube 자막 입력 길이를 제한해 불필요한 토큰 사용 감소
- 실패 단계만 재처리할 수 있도록 원문 저장과 발행 로그를 분리

**플랫폼별 글자 수와 포맷 차이**
- 요약 원문과 플랫폼별 발행 데이터를 분리
- 성공·실패 상태 및 외부 게시 ID를 기록해 채널별 독립 재시도 가능하게 개선

### 성과
- 반복적인 뉴스 수집·요약·발행 작업 자동화
- AI, 자동화, DB, Docker 운영 환경을 결합한 개인 서비스 구축
- 외부 API 장애를 고려한 운영형 워크플로우 설계 경험 확보

</details>

<details>
<summary><strong>📌 Crypto Discord Bot</strong></summary>

- **GitHub:** https://github.com/sedoll/crypto-discord
- **역할:** 1인 개발
- **Tech:** Python, Java(Spring Boot), Docker, Linux, Discord API, Bithumb API, OpenAI API

### 프로젝트 소개
Discord에서 암호화폐 자산 및 거래 정보를 조회하고 GPT 기반 코멘트를 제공하는 서비스입니다. Python Discord Bot과 Spring Boot API 서버를 분리하고 Docker Compose로 운영 환경을 구성했습니다.

### 주요 기여
- Discord Bot 명령어 및 사용자 요청 처리 기능 구현
- Spring Boot 기반 내부 API 서버 구축
- Bithumb API 연동 및 자산 데이터 조회 기능 개발
- GPT 기반 AI 코멘트 기능 구현
- Docker Compose 기반 멀티 컨테이너 배포 및 내부 네트워크 구성

### 핵심 문제 해결
**GPT 모델 버전별 API 구조 차이**
- 모델별 요청·응답 처리를 분리하고 공통 응답 처리 영역 구성
- 모델 변경 시 영향 범위를 최소화하도록 구조 개선
- AI 호출 실패 시 기본 기능이 유지되도록 예외 처리 추가

**Bot과 API 서버의 운영 복잡도 및 보안**
- Docker Compose로 실행 환경과 네트워크를 통합 관리
- `.env` 및 secrets 기반으로 민감 정보 분리
- 내부 API용 Access Key를 적용해 외부 접근 제한

### 성과
- Spring Boot + Python 멀티 서비스 운영 경험 확보
- Docker/Linux 기반 배포 및 내부 네트워크 구성 경험 강화
- 거래소 및 AI API 연동 서비스 설계 경험 확보

</details>

<details>
<summary><strong>📌 OpenCV_SEnow</strong></summary>

- **GitHub:** https://github.com/sedoll/OpenCV_SEnow
- **Blog:** https://blog.naver.com/tmvmffpsej/223128389009
- **역할:** 1인 개발
- **Tech:** Python, OpenCV, MediaPipe, Dlib

### 프로젝트 소개
OpenCV와 얼굴 랜드마크 인식 기술을 활용해 실시간 카메라 필터 및 얼굴 스티커 기능을 구현한 컴퓨터 비전 프로젝트입니다.

### 주요 기여
- 얼굴 랜드마크 추출 및 실시간 좌표 계산
- 얼굴 위치 기반 스티커·필터 적용 기능 개발
- 얼굴 이동과 각도 변화에 따른 필터 좌표 보정
- 실시간 영상 프레임 처리 성능 개선

### 핵심 문제 해결
**얼굴 움직임에 따른 필터 위치 오차와 프레임 저하**
- 랜드마크 좌표를 기준으로 필터 위치를 동적으로 계산
- 프레임별 좌표 보정과 불필요한 처리 제거를 통해 실시간 처리 안정성 개선

### 성과
- OpenCV 기반 실시간 영상 처리 구조 이해
- 얼굴 랜드마크 기반 좌표 처리 및 성능 최적화 경험 확보

</details>

---

# 🎓 교육 및 학력 (Education)

## 에듀테크 풀스택 AI 개발자 양성 과정 (천재교육)
- **위치:** 서울특별시 금천구
- **기간:** 2023.07 ~ 2023.12
- **내용:** Java / Spring Boot 기반 백엔드, 프론트엔드, 데이터베이스를 활용한 웹 서비스 개발 과정 수료 및 AI 기반 교육 서비스 프로젝트 수행

## 국립 공주대학교
- **학과:** 컴퓨터공학과
- **학위:** 학사
- **기간:** 2021.03 ~ 2023.08

## 유한대학교
- **학과:** 전자공학과
- **학위:** 전문학사
- **기간:** 2017.03 ~ 2021.02

---

# 🎖 자격증 및 수상

## 📜 자격증
- 정보처리기사 (2022)
- 운전면허 2종 보통 (2019)

## 🏆 수상
- [교내 캡스톤 경진대회 2등](https://github.com/sedoll/ai_gym) (2020)

---

# 📌 개발 키워드

`Java / Spring Boot` · `Full Stack` · `AI API` · `서비스 운영` · `장애 대응` · `자동화` · `Docker / Linux` · `데이터 수집`

<div>
<img src="https://komarev.com/ghpvc/?username=sedoll&&style=flat-square" align="center" />
</div>
