<h1 align="center">안녕하세요, 백엔드 개발자 태현입니다 👋</h1>

<p align="center">
  <strong>Backend Developer · Python · Java · AI Automation</strong><br/>
  복잡한 데이터를 정리하고, 반복적인 업무를 자동화하는 개발자입니다.<br/>
  웹 백엔드와 데이터 처리, AI 서비스 연동을 경험했습니다.
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Taehyoning&style=flat&color=555555" alt="Profile views" />
</p>

---

## 🎯 What I Focus On

- **보험상품 매칭:** 보험사명·상품명 정규화, 유사도 기반 후보 추천 및 가입일·판매기간 비교
- **보장 판정 자동화:** 치아파절 보장 포함/제외/검토 분류, 금액 계산 및 예외 조건 처리
- **백엔드 개발:** Python/FastAPI 기반 REST API, Java/JSP/Servlet 및 MyBatis 활용
- **업무 데이터 처리:** CSV·DB 데이터 가공, SQLite 기반 판정 데이터 구성, 검증 스크립트 작성

---

## 🚀 Highlight Projects

### 01. 보험상품 유사도 검증 및 치아파절 보장 자동판정 시스템

**실무 프로젝트 | Python · FastAPI · Pandas · MySQL · SQLite**

보험 계약정보를 기반으로 유사한 보험상품 후보를 탐색하고, 보장 항목과 판정 규칙을 바탕으로 치아파절 보장 여부 및 금액 계산을 지원하는 업무 시스템입니다.

- 보험사명·상품명 표기 차이를 정규화하고 후보를 유사도 기반으로 정렬
- 가입일 및 상품 판매기간을 고려한 후보 검증 흐름 구성
- 치아파절 보장 항목을 포함·제외·검토 필요로 분류하는 규칙 및 예외 조건 처리
- 계산 결과 및 검토 데이터를 생성하는 watcher/runtime 처리 흐름 개발
- 테스트·스모크 검증 스크립트 및 장애 분석을 위한 보조 로직 구성

> **공개 범위:** 실제 서비스가 운영 중인 회사 프로젝트입니다. 소스 코드, 계약 데이터, 내부 화면과 세부 판정 기준은 공개하지 않습니다. 위 내용은 외부 설명 가능한 수준으로 일반화한 구현 경험입니다.

### 02. BabyHands — AI 기반 수어 학습 웹 서비스

**팀 프로젝트 | Java · JSP/Servlet · MyBatis · Oracle · Python · FastAPI**

수어 학습과 테스트 결과를 확인할 수 있는 웹 서비스로, 저는 주로 **웹 백엔드와 사용자별 학습 데이터 조회 기능**을 담당했습니다.

- 로그인 및 회원 관련 백엔드 처리
- 사용자별 학습 결과 조회와 테스트 결과 페이지 연동
- 점수 기반 랭킹 및 기록 조회 기능 구현
- JSP 화면과 데이터베이스 조회 로직 연결
- 수어 인식 모델 관련 실험 및 팀원과의 연동 협업

**팀 프로젝트 참고 저장소** (본인 단독 작업물이 아님):
[Web](https://github.com/pobiq/babyhands-web) · [AI](https://github.com/pobiq/babyhands-python)

### 03. 의료 문서 PDF 개인정보 비식별화

**실무 프로젝트 경험 | Python · PyMuPDF · 정규표현식**

텍스트 기반 진료기록 PDF에서 개인정보로 추정되는 영역을 탐지하고, 검수용 미리보기와 비식별화 파일 생성을 지원하는 기능을 구현했습니다.

- PDF 텍스트 블록 및 좌표 추출
- 키워드·패턴 기반 개인정보 후보 탐지
- 원문 보존 범위를 고려한 제거 영역 판정
- Preview PDF와 비식별화 결과 PDF 생성

> 스캔 이미지 PDF에 대한 OCR 완전 지원이나 비식별화 정확도를 보장하는 프로젝트로 소개하지 않습니다.

---

## 🛠 Tech Stack

### 💻 Backend / Languages
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Java-007396?logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/JSP%20%2F%20Servlet-4F5B93" alt="JSP Servlet" />
  <img src="https://img.shields.io/badge/MyBatis-BA2F2F" alt="MyBatis" />
</p>

### 🗄 Database / Data
<p>
  <img src="https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white" alt="MySQL" />
  <img src="https://img.shields.io/badge/Oracle-F80000?logo=oracle&logoColor=white" alt="Oracle" />
  <img src="https://img.shields.io/badge/SQLite-003B57?logo=sqlite&logoColor=white" alt="SQLite" />
  <img src="https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white" alt="Pandas" />
  <img src="https://img.shields.io/badge/SQLAlchemy-D71F00" alt="SQLAlchemy" />
</p>

### 🤖 AI / Tools
<p>
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white" alt="TensorFlow" />
  <img src="https://img.shields.io/badge/MediaPipe-0097A7" alt="MediaPipe" />
  <img src="https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white" alt="GitHub" />
</p>

---

## 📚 Problem Solving

- [1Day1Question — 백준·프로그래머스 문제 풀이 기록](https://github.com/Taehyoning/1Day1Question)

---

## 📊 GitHub Activity

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Taehyoning&theme=github-dark-blue&hide_border=true" alt="GitHub contribution streak" />
</p>

<p align="center"><sub>실무 프로젝트 저장소는 비공개이며, 공개 저장소만으로 모든 개발 경험이 드러나지는 않습니다.</sub></p>
