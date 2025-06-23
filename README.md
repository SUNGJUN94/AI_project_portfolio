# 🎓 AI Project Portfolio - SUNGJUN94

안녕하십니까.  
저의 이력서를 확인해주시어 해당 레포에 방문해주셔서 감사합니다.  
이 레포지토리는 AI 기반 데이터 분석 및 웹 응용 프로젝트를 소개하기 위한 포트폴리오 공간입니다.  
직접 기획, 개발, 배포까지 수행한 프로젝트를 중심으로 구성되어 있습니다.

---
⚠️ 본 프로젝트는 현재 " 비공개 저장소 "로 운영되고 있습니다.  
보안 및 저작권 보호를 위해 소스코드는 공개하지 않았으며,  
관심 있는 분들께는 아래 이메일을 통해 GitHub 접근 권한을 개별 제공 드립니다.

📩 **이메일 요청 : fiwns7942@gmail.com**

귀사의 무궁한 발전과 번영을 기원합니다.
---
---
## 📌 Big Epoch 주식 예측 프로젝트 요약

1. [📈 Quant Trading Prediction (퀀트 주가 예측 시스템)](#-1-quant-trading-prediction-퀀트-주가-예측-시스템)
2. [🤖 AI Financial Assistant (금융 전문 챗봇)](#-2-ai-financial-assistant-금융-전문-챗봇)
3. [💬 Investment Community Platform (투자 커뮤니티)](#-3-investment-community-platform-투자-커뮤니티)
4. [📊 Technical Analysis Chart System (기술적 분석 차트)](#-4-technical-analysis-chart-system-기술적-분석-차트)
5. [👤 User Management System (사용자 관리 시스템)](#-5-user-management-system-사용자-관리-시스템)
6. [🏗️ System Architecture & DevOps](#-6-system-architecture-&-devops)
7. [🔐 보안/접근 관련 안내](#-보안접근-관련-안내)
8. [🧠 Why This Portfolio?](#-why-this-portfolio)
9. [📈 프로젝트 성과 및 기술적 도전](#-프로젝트-성과-및-기술적-도전)

### 🎥 프로젝트 영상 시연 보기
[📺 Click to watch demo](https://youtu.be/your_video_link) 

---

## 📌 Fridge Recipick_KR 프로젝트 목차

1. [🍳 11. AI Recipe Recommender (개인화된 레시피 추천 엔진)](#-11-AI-레시피-추천-시스템)
2. [💬 12. AI Cooking Assistant (요리 상담 챗봇)](#-12-AI-요리-상담-챗봇)
3. [🥬 13. My Fridge Manager (내 냉장고 관리 시스템)](#-13-내-냉장고-관리-시스템)
4. [⭐ 14. Favorite & Category System (즐겨찾기 및 카테고리)](#-14-즐겨찾기-및-카테고리-시스템)
5. [📰 15. Cooking News Feed (요리 뉴스 시스템)](#-15-요리-뉴스-시스템)
6. [👤 16. User Management System (사용자 관리 시스템)](#-16-사용자-관리-시스템)
7. [🏗️ 17. System Architecture & DevOps](#-17-시스템-아키텍처-&-devops)
8. [🧠 18. Why This Portfolio?](#-19-why-this-portfolio)
9.[📈 19. 프로젝트 성과 및 기술적 도전](#-20-프로젝트-성과-및-기술적-도전)

### 🎥 프로젝트 영상 시연 보기  
[📺 Click to watch demo](https://youtu.be/your_video_link)

---
---


## 📈 1. Quant Trading Prediction (퀀트 주가 예측 시스템)

> 국내 주식 시장 데이터를 기반으로 한 **딥러닝 기반 주가 예측 시스템**

### 🛠️ 기술스택
- **Backend**: Python, Django 5.2.1, MySQL
- **AI/ML**: TensorFlow 2.19.0, LSTM, Prophet 1.1.6, Scikit-learn 1.6.1
- **Data Processing**: Pandas 2.2.3, NumPy 1.26.4, Pandas-TA 0.3.14b0
- **Data Collection**: PyKRX 1.0.51, FinanceDataReader, DART API
- **Visualization**: Plotly 6.0.1, Chart.js
- **Scheduling**: APScheduler 3.11.0, Django-APScheduler

### 🎯 주요 기능
- **📊 다중 시장 예측**: KOSPI/KOSDAQ 시장별 전용 LSTM 모델
- **📈 기술적 지표 분석**: RSI, MACD, 볼린저밴드, 이동평균 등 20+ 지표
- **📰 뉴스 감성분석**: 네이버 뉴스 API 기반 실시간 뉴스 수집 및 분석
- **🏢 공시 정보 통합**: DART API를 통한 기업 공시 정보 자동 수집
- **🤖 자동화 시스템**: 매일 자동 데이터 수집 및 예측 모델 업데이트
- **📱 실시간 차트**: 인터랙티브 주가 차트 및 기술적 지표 시각화

### 🔧 핵심 구현 사항
- **LSTM 모델 아키텍처**: 60일 시퀀스 기반 다층 LSTM (50-50-1 구조)
- **피처 엔지니어링**: OHLCV + 기술적 지표 + 투자자별 거래량 + 펀더멘털 데이터
- **데이터 파이프라인**: 일별 자동 데이터 수집 → 전처리 → 모델 학습 → 예측 결과 DB 저장
- **실시간 예측**: 사용자 입력 종목에 대한 향후 5일 예측 제공

### 📌 관련 디렉토리
- `predict_info/`: 예측 시스템 핵심 모듈
- `data/kosdaq_data/`: 학습용 주가 데이터
- `predict_info/management/commands/`: 자동화 스케줄러


🔝 [프로젝트 요약으로 이동](#-Big-Epoch-주식-예측-프로젝트-요약)

---

## 🤖 2. AI Financial Assistant (금융 전문 챗봇)

> **GPT-4 기반 금융 전문 AI 어시스턴트**

### 🛠️ 기술스택
- **AI**: OpenAI GPT-4 Turbo, OpenAI API 1.84.0
- **Backend**: Django, Python
- **Frontend**: JavaScript, AJAX
- **Security**: CSRF Protection, 욕설 필터링

### 🎯 주요 기능
- **💬 금융 전문 상담**: 주식, 투자, 경제, 금융상품, 부동산, 재테크 전문 답변
- **🛡️ 콘텐츠 필터링**: 욕설 및 부적절한 내용 자동 필터링
- **🌐 한국어 최적화**: 금융 전문 용어 및 한국 시장 특성 반영
- **⚡ 실시간 응답**: 비동기 처리로 빠른 응답 속도

### 🔧 핵심 구현 사항
- **시스템 프롬프트 엔지니어링**: 금융 전문가 역할 정의
- **욕설 필터링 시스템**: 커스텀 필터링 로직 구현
- **에러 핸들링**: API 호출 실패 시 graceful degradation

### 📌 관련 디렉토리
- `chatbot/`: 챗봇 핵심 모듈
- `community/text/`: 욕설 필터링 데이터


🔝 [프로젝트 요약으로 이동](#-Big-Epoch-주식-예측-프로젝트-요약)

---

## 💬 3. Investment Community Platform (투자 커뮤니티)

> **실시간 투자 정보 공유 및 커뮤니티 플랫폼**

### 🛠️ 기술스택
- **Backend**: Django, MySQL
- **Frontend**: Bootstrap, JavaScript
- **Data Integration**: DART API, 네이버 뉴스 API
- **File Handling**: Pillow (이미지 처리)

### 🎯 주요 기능
- **📝 자유게시판**: 카테고리별 게시글 작성/수정/삭제
- **💬 댓글 시스템**: 계층형 댓글 및 알림 기능
- **👍 소셜 기능**: 좋아요, 걱정돼요, 조회수 추적
- **📰 실시간 뉴스**: 네이버 뉴스 API 기반 자동 뉴스 수집
- **🏢 공시 정보**: DART API 기반 기업 공시 자동 수집
- **🔔 알림 시스템**: 댓글 작성 시 실시간 알림

### 🔧 핵심 구현 사항
- **실시간 데이터 수집**: 스케줄러를 통한 뉴스/공시 자동 수집
- **커뮤니티 관리**: 관리자 게시판, 사용자 권한 관리
- **이미지 업로드**: 프로필 이미지, 게시글 첨부 이미지 처리
- **검색 및 필터링**: 카테고리별, 날짜별 게시글 필터링

### 📌 관련 디렉토리
- `community/`: 커뮤니티 핵심 모듈
- `community/management/commands/`: 데이터 수집 자동화


🔝 [프로젝트 요약으로 이동](#-Big-Epoch-주식-예측-프로젝트-요약)

---

## 📊 4. Technical Analysis Chart System (기술적 분석 차트)

> **고급 기술적 분석 지표를 제공하는 인터랙티브 차트 시스템**

### 🛠️ 기술스택
- **Frontend**: Chart.js, Plotly.js, JavaScript
- **Backend**: Django, Python
- **Data Processing**: Pandas-TA, NumPy

### 🎯 주요 기능
- **📈 캔들스틱 차트**: OHLCV 데이터 시각화
- **📊 기술적 지표**: RSI, MACD, 볼린저밴드, 이동평균선
- **🎛️ 인터랙티브 컨트롤**: 지표별 표시/숨김 토글
- **📱 반응형 디자인**: 모바일/데스크톱 최적화
- **🔄 실시간 업데이트**: AJAX 기반 데이터 갱신

### 🔧 핵심 구현 사항
- **다중 차트 레이아웃**: 메인 차트 + 보조지표 차트 구성
- **동적 지표 계산**: 클라이언트 사이드 기술적 지표 계산
- **차트 인터랙션**: 줌, 팬, 툴팁 기능

### 📌 관련 디렉토리
- `chart/`: 차트 시스템 핵심 모듈
- `static/js/chart.js`: 차트 인터랙션 로직


🔝 [프로젝트 요약으로 이동](#-Big-Epoch-주식-예측-프로젝트-요약)

---

## 👤 5. User Management System (사용자 관리 시스템)

> **완전한 사용자 인증 및 프로필 관리 시스템**

### 🛠️ 기술스택
- **Backend**: Django, MySQL
- **Authentication**: Django Custom User Model
- **Security**: Argon2 Password Hashing
- **File Handling**: Pillow

### 🎯 주요 기능
- **🔐 사용자 인증**: 회원가입, 로그인, 로그아웃
- **🔍 계정 찾기**: 아이디/비밀번호 찾기
- **👤 프로필 관리**: 프로필 이미지 업로드, 정보 수정
- **⭐ 즐겨찾기**: 관심 종목 등록/관리
- **📊 마이페이지**: 사용자 활동 내역 및 설정

### 🔧 핵심 구현 사항
- **커스텀 유저 모델**: 확장 가능한 사용자 정보 구조
- **보안 강화**: Argon2 해시, 세션 관리
- **파일 업로드**: 프로필 이미지 처리 및 최적화

### 📌 관련 디렉토리
- `account/`: 인증 시스템
- `mypage/`: 사용자 프로필 관리


🔝 [프로젝트 요약으로 이동](#-Big-Epoch-주식-예측-프로젝트-요약)

---

## 🏗️ 6. System Architecture & DevOps

### 🛠️ 인프라 구성
- **서버**: AWS EC2 (Ubuntu 22.04)
- **데이터베이스**: MySQL 8.0
- **웹서버**: Django Development Server
- **스케줄링**: APScheduler (백그라운드 작업)

### 🔧 자동화 시스템
- **일별 데이터 수집**: 주가, 뉴스, 공시 정보 자동 수집
- **모델 재학습**: 주기적 예측 모델 성능 업데이트
- **데이터베이스 관리**: 자동 백업 및 정리

### 📊 데이터 파이프라인
```
외부 API (PyKRX, DART, 네이버뉴스) 
    ↓
데이터 수집 (APScheduler)
    ↓
전처리 및 피처 엔지니어링
    ↓
LSTM 모델 학습/예측
    ↓
결과 저장 (MySQL)
    ↓
웹 인터페이스 제공
```


🔝 [프로젝트 요약으로 이동](#-Big-Epoch-주식-예측-프로젝트-요약)

---

## 🔐 보안/접근 관련 안내

- 본 저장소는 **일부 API 키, 민감한 경로 등은 제거**된 상태로 제공됩니다.
- 전체 실행 환경/설정이 필요하신 경우, 아래 연락처 또는 이력서에 명시된 인증 키를 통해 전체 접근 권한을 요청하실 수 있습니다.

📩 Contact: sungjun94@gmail.com  
🔑 Resume Key Access: 이력서 내 별도 안내 참고


🔝 [프로젝트 요약으로 이동](#-Big-Epoch-주식-예측-프로젝트-요약)

---

## 🧠 Why This Portfolio?

### 💼 실무 중심 프로젝트 구조
- **풀스택 개발 경험**: Frontend부터 Backend, AI/ML까지 전체 스택 구현
- **실제 서비스 배포**: AWS EC2 기반 실제 운영 환경 구축
- **데이터 엔지니어링**: ETL 파이프라인 설계 및 구현

### 🤖 AI/ML 전문성
- **딥러닝 모델 개발**: LSTM 기반 시계열 예측 모델 구현
- **자연어 처리**: GPT-4 API를 활용한 전문 챗봇 개발
- **데이터 분석**: 금융 데이터 전처리 및 피처 엔지니어링

### 🔄 자동화 및 운영
- **스케줄링 시스템**: APScheduler를 통한 백그라운드 작업 자동화
- **데이터 파이프라인**: 실시간 데이터 수집 및 처리 시스템
- **모니터링**: 로깅 및 에러 핸들링 시스템

### 🌐 현대적 웹 개발
- **반응형 디자인**: Bootstrap 기반 모바일 최적화
- **실시간 인터랙션**: AJAX 기반 비동기 데이터 처리
- **사용자 경험**: 직관적인 UI/UX 설계


🔝 [프로젝트 요약으로 이동](#-Big-Epoch-주식-예측-프로젝트-요약)

---

## 📈 프로젝트 성과 및 기술적 도전

### 🎯 주요 성과
- **다중 시장 예측**: KOSPI/KOSDAQ 시장별 전용 모델로 정확도 향상
- **실시간 시스템**: 24/7 자동 데이터 수집 및 예측 업데이트
- **사용자 중심 설계**: 투자자 관점에서 필요한 기능 우선 구현

### 🚀 기술적 도전과 해결
- **대용량 데이터 처리**: 수백만 건의 주가 데이터 효율적 처리
- **실시간 예측**: 사용자 요청 시 즉시 예측 결과 제공
- **API 통합**: 다양한 외부 API (DART, 네이버뉴스, PyKRX) 통합
- **모델 성능 최적화**: LSTM 모델 하이퍼파라미터 튜닝 및 성능 개선


🔝 [프로젝트 요약으로 이동](#-Big-Epoch-주식-예측-프로젝트-요약)

---

---

---

## 🎯 주요 기능 상세

### 🤖 11. AI 레시피 추천 시스템
**개인화된 레시피 추천 엔진**

🛠️ **기술 구현**
- 사용자 재료 분석 기반 추천 알고리즘
- 재료 기반 레시피 매칭 시스템
- 조회수 및 인기도 기반 추천

### 🎯 핵심 기능
- 🤖 **레시피 추천**: 사용자 실 냉장고 기반 개인화 레시피 추천
- 💬 **AI 요리 챗봇**: GPT-3.5 기반 요리 전문 챗봇
- 🥬 **내 냉장고 관리**: 재료 기반 레시피 검색 및 관리
- ⭐ **즐겨찾기 시스템**: 카테고리별 레시피 즐겨찾기 관리
- 📰 **요리 뉴스**: 실시간 요리 관련 뉴스 수집 및 공유
- 📊 **인기 레시피**: 조회수 기반 인기 레시피 추천

## 🛠️ 기술 스택

### Backend
- **Framework**: Django 5.2.1
- **Database**: MySQL 8.0
- **Authentication**: Django Custom User Model
- **Security**: Argon2 Password Hashing

### AI/ML
- **AI Chat**: OpenAI GPT-3.5 Turbo
- **API**: OpenAI API 1.84.0
- **Data Processing**: Pandas 2.2.3, NumPy 1.26.4

### Frontend
- **Template Engine**: Django Templates
- **CSS Framework**: Bootstrap
- **JavaScript**: Vanilla JS, AJAX
- **Charts**: Chart.js (향후 확장 예정)

### External APIs
- **News API**: 네이버 뉴스 API
- **Recipe Data**: CSV 기반 레시피 데이터베이스

### Development Tools
- **Environment**: Python-dotenv 1.1.0
- **File Handling**: Pillow 11.2.1 (이미지 처리)
- **Scheduling**: APScheduler 3.11.0

## 🏗️ 시스템 아키텍처

### 📊 데이터베이스 구조
```
User (Django Auth)
├── UserProfile (보안 질문/답변)
├── Favorite (즐겨찾기 레시피)
│   └── FavoriteCategory (카테고리)
├── RecentIngredient (최근 검색 재료)
├── NewsLike (뉴스 좋아요)
├── NewsScrap (뉴스 스크랩)
└── RecipeView (레시피 조회수)
```

### 🔄 데이터 플로우
```
사용자 입력 → Django Views → AI Processing → Database → Response
    ↓
레시피 데이터 (CSV) → 검색/필터링 → 개인화 추천
    ↓
네이버 뉴스 API → 실시간 뉴스 수집
```

🔧 **핵심 구현 사항**
- CSV 데이터 기반 레시피 데이터베이스 (24,000+ 레시피)
- 사용자 행동 패턴 분석 (조회수, 즐겨찾기)
- 실시간 추천 알고리즘

📌 **관련 디렉토리**
- `main/views.py`: 추천 로직 구현
- `DATA/TB_RECIPE_SEARCH_241226.csv`: 레시피 데이터베이스


🔝 [프로젝트 요약으로 이동](#-Fridge-Recipick_KR-프로젝트-목차)

---

### 💬 12. AI 요리 상담 챗봇
**GPT-3.5 기반 요리 전문 AI 어시스턴트**

🛠️ **기술 스택**
- **AI**: OpenAI GPT-3.5 Turbo
- **Backend**: Django, Python
- **Frontend**: JavaScript, AJAX
- **Security**: CSRF Protection

🎯 **주요 기능**
- 🍳 **요리 상담**: 레시피, 조리법, 재료 관련 전문 답변
- 🛡️ **콘텐츠 필터링**: 부적절한 내용 자동 필터링
- 🌐 **한국어 최적화**: 요리 전문 용어 및 한국 요리 특성 반영
- ⚡ **실시간 응답**: 비동기 처리로 빠른 응답 속도

🔧 **핵심 구현 사항**
- 시스템 프롬프트 엔지니어링: 요리사 AI 역할 정의
- 토큰 제한: 400 토큰으로 간결한 답변 유도
- 에러 핸들링: API 호출 실패 시 graceful degradation

📌 **관련 디렉토리**
- `main/views.py`: AI 챗봇 핵심 로직
- `main/templates/ai_chat.html`: 챗봇 인터페이스


🔝 [프로젝트 요약으로 이동](#-Fridge-Recipick_KR-프로젝트-목차)

---

### 🥬 13. 내 냉장고 관리 시스템
**개인 냉장고 재료 관리 및 레시피 검색**

🛠️ **기술 스택**
- **Backend**: Django, MySQL
- **Frontend**: Bootstrap, JavaScript
- **Data Processing**: Pandas, NumPy

🎯 **주요 기능**
- 📝 **재료 관리**: 개인 냉장고 재료 추가/삭제/관리
- 🔍 **레시피 검색**: 보유 재료로 가능한 레시피 검색
- 📊 **재료 통계**: 자주 사용하는 재료 분석
- 🗑️ **일괄 삭제**: 전체 재료 초기화 기능

🔧 **핵심 구현 사항**
- 재료 기반 레시피 매칭 알고리즘
- 최근 검색 재료 자동 저장
- 사용자별 개인화된 재료 관리

📌 **관련 디렉토리**
- `main/views.py`: 냉장고 관리 로직
- `main/templates/my_fridge.html`: 냉장고 인터페이스


🔝 [프로젝트 요약으로 이동](#-Fridge-Recipick_KR-프로젝트-목차)

---

### ⭐ 14. 즐겨찾기 및 카테고리 시스템
**개인화된 레시피 즐겨찾기 관리**

🛠️ **기술 스택**
- **Backend**: Django, MySQL
- **Frontend**: JavaScript, AJAX
- **UI**: Bootstrap

🎯 **주요 기능**
- ❤️ **즐겨찾기**: 관심 레시피 즐겨찾기 등록/해제
- 📁 **카테고리 관리**: 개인 카테고리 생성/삭제/관리
- 🏷️ **태그 시스템**: 카테고리별 레시피 분류
- 📊 **즐겨찾기 통계**: 카테고리별 레시피 현황

🔧 **핵심 구현 사항**
- 다대다 관계 모델링 (Favorite ↔ FavoriteCategory)
- 실시간 AJAX 기반 즐겨찾기 토글
- 사용자별 개인 카테고리 관리

📌 **관련 디렉토리**
- `main/models.py`: 즐겨찾기 모델 정의
- `main/views.py`: 즐겨찾기 관리 로직


🔝 [프로젝트 요약으로 이동](#-Fridge-Recipick_KR-프로젝트-목차)

---

### 📰 15. 요리 뉴스 시스템
**실시간 요리 관련 뉴스 수집 및 공유**

🛠️ **기술 스택**
- **External API**: 네이버 뉴스 API
- **Backend**: Django, Python
- **Frontend**: Bootstrap, JavaScript
- **Data Processing**: JSON, HTML 파싱

🎯 **주요 기능**
- 📰 **실시간 뉴스**: 네이버 뉴스 API 기반 요리 뉴스 수집
- 🔍 **뉴스 검색**: 키워드 기반 뉴스 검색
- 👍 **소셜 기능**: 뉴스 좋아요, 스크랩 기능
- 📱 **페이지네이션**: 대용량 뉴스 데이터 효율적 표시

🔧 **핵심 구현 사항**
- 네이버 뉴스 API 통합
- HTML 태그 제거 및 데이터 정제
- 사용자별 좋아요/스크랩 상태 관리
- 페이지네이션 및 검색 기능

📌 **관련 디렉토리**
- `main/views.py`: 뉴스 검색 및 관리 로직
- `main/templates/news_search.html`: 뉴스 인터페이스


🔝 [프로젝트 요약으로 이동](#-Fridge-Recipick_KR-프로젝트-목차)

---

### 👤 16. 사용자 관리 시스템
**완전한 사용자 인증 및 프로필 관리**

🛠️ **기술 스택**
- **Backend**: Django, MySQL
- **Authentication**: Django Custom User Model
- **Security**: Argon2 Password Hashing
- **File Handling**: Pillow

🎯 **주요 기능**
- 🔐 **사용자 인증**: 회원가입, 로그인, 로그아웃
- 🔍 **계정 찾기**: 아이디/비밀번호 찾기 (보안 질문)
- 👤 **프로필 관리**: 사용자 정보 관리
- 🛡️ **보안 강화**: Argon2 해시, 세션 관리

🔧 **핵심 구현 사항**
- 커스텀 유저 프로필 모델
- 보안 질문/답변 기반 비밀번호 찾기
- 중복 검사 (아이디, 이메일)

📌 **관련 디렉토리**
- `main/models.py`: 사용자 모델 정의
- `main/views.py`: 인증 로직
- `main/templates/`: 인증 관련 템플릿


🔝 [프로젝트 요약으로 이동](#-Fridge-Recipick_KR-프로젝트-목차)

---

## 🏗️ 17. 시스템 아키텍처 & DevOps

### 🛠️ 인프라 구성
- **서버**: AWS EC2 (Ubuntu 22.04)
- **데이터베이스**: MySQL 8.0
- **웹서버**: Django Development Server
- **스케줄링**: APScheduler (백그라운드 작업)

### 🔧 자동화 시스템
- **데이터 수집**: 뉴스 API 자동 수집
- **사용자 활동**: 조회수, 즐겨찾기 통계 자동 업데이트
- **데이터베이스 관리**: 자동 백업 및 정리

### 📊 데이터 파이프라인
```
외부 API (네이버뉴스) 
    ↓
데이터 수집 (Django Views)
    ↓
전처리 및 데이터 정제
    ↓
데이터베이스 저장 (MySQL)
    ↓
웹 인터페이스 제공
```


🔝 [프로젝트 요약으로 이동](#-Fridge-Recipick_KR-프로젝트-목차)

---

## 🧠 18. Why This Portfolio?

### 💼 실무 중심 프로젝트 구조
- **풀스택 개발 경험**: Frontend부터 Backend, AI/ML까지 전체 스택 구현
- **실제 서비스 배포**: AWS EC2 기반 실제 운영 환경 구축
- **데이터 엔지니어링**: CSV 데이터 처리 및 API 통합

### 🤖 AI/ML 전문성
- **자연어 처리**: GPT-3.5 API를 활용한 전문 챗봇 개발
- **추천 시스템**: 사용자 행동 기반 개인화 추천 알고리즘
- **데이터 분석**: 레시피 데이터 전처리 및 분석

### 🔄 자동화 및 운영
- **API 통합**: 네이버 뉴스 API 등 외부 서비스 통합
- **데이터 파이프라인**: 실시간 데이터 수집 및 처리 시스템
- **모니터링**: 로깅 및 에러 핸들링 시스템

### 🌐 현대적 웹 개발
- **반응형 디자인**: Bootstrap 기반 모바일 최적화
- **실시간 인터랙션**: AJAX 기반 비동기 데이터 처리
- **사용자 경험**: 직관적인 UI/UX 설계


🔝 [프로젝트 요약으로 이동](#-Fridge-Recipick_KR-프로젝트-목차)

---

## 📈 19. 프로젝트 성과 및 기술적 도전

### 🎯 주요 성과
- **개인화 추천**: 사용자 취향 기반 맞춤형 레시피 추천 시스템
- **실시간 시스템**: 24/7 자동 뉴스 수집 및 업데이트
- **사용자 중심 설계**: 요리 애호가 관점에서 필요한 기능 우선 구현

### 🚀 기술적 도전과 해결
- **대용량 데이터 처리**: 24,000+ 레시피 데이터 효율적 처리
- **실시간 추천**: 사용자 요청 시 즉시 개인화 추천 제공
- **API 통합**: 네이버 뉴스 API 등 다양한 외부 서비스 통합
- **사용자 경험 최적화**: 직관적인 인터페이스 및 빠른 응답 속도


🔝 [프로젝트 요약으로 이동](#-Fridge-Recipick_KR-프로젝트-목차)

---

## 🎥 프로젝트 영상 시연 보기

[📺 Click to watch demo](링크 추가 예정)


🔝 [프로젝트 요약으로 이동](#-Fridge-Recipick_KR-프로젝트-목차)

---

## 📁 프로젝트 구조

```
recipy/
├── dashboard/                 # Django 프로젝트 설정
│   ├── settings.py           # 프로젝트 설정
│   ├── urls.py               # 메인 URL 설정
│   └── wsgi.py               # WSGI 설정
├── main/                     # 메인 애플리케이션
│   ├── models.py             # 데이터베이스 모델
│   ├── views.py              # 뷰 로직
│   ├── urls.py               # URL 라우팅
│   ├── templates/            # HTML 템플릿
│   └── migrations/           # 데이터베이스 마이그레이션
├── DATA/                     # 레시피 데이터
│   └── TB_RECIPE_SEARCH_241226.csv
├── static/                   # 정적 파일
│   └── images/               # 이미지 파일
├── requirements.txt          # Python 의존성
└── manage.py                # Django 관리 스크립트
```

---



프로젝트 하나하나에 담긴 고민과 집념을 통해 더 큰 가치를 만들고자 했습니다.

이 포트폴리오가 귀사와의 좋은 인연으로 이어지기를 바랍니다.

끝까지 읽어주셔서 너무나 감사합니다.
