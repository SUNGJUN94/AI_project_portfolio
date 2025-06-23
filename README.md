# 🎓 AI Project Portfolio - SUNGJUN94

안녕하세요!  
이 GitHub 레포지토리는 **AI 기반 데이터 분석 및 웹 응용 프로젝트**를 소개하기 위한 포트폴리오 공간입니다.  
직접 기획, 개발, 배포까지 진행한 프로젝트를 포함하고 있습니다.
---

## 📌 프로젝트 요약

1. [📈 Quant Trading Prediction (퀀트 주가 예측 시스템)](#-1-quant-trading-prediction-퀀트-주가-예측-시스템)
2. [🤖 AI Financial Assistant (금융 전문 챗봇)](#-2-ai-financial-assistant-금융-전문-챗봇)
3. [💬 Investment Community Platform (투자 커뮤니티)](#-3-investment-community-platform-투자-커뮤니티)
4. [📊 Technical Analysis Chart System (기술적 분석 차트)](#-4-technical-analysis-chart-system-기술적-분석-차트)
5. [👤 User Management System (사용자 관리 시스템)](#-5-user-management-system-사용자-관리-시스템)
6. [🏗️ System Architecture & DevOps](#-6-system-architecture--devops)
7. [🔐 보안/접근 관련 안내](#-보안접근-관련-안내)
8. [🧠 Why This Portfolio?](#-why-this-portfolio)
9. [📈 프로젝트 성과 및 기술적 도전](#-프로젝트-성과-및-기술적-도전)

### 🎥 프로젝트 영상 시연 보기
[📺 Click to watch demo](https://youtu.be/your_video_link) 

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


🔝 [프로젝트 요약으로 이동](#-프로젝트-요약)

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


🔝 [프로젝트 요약으로 이동](#-프로젝트-요약)

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


🔝 [프로젝트 요약으로 이동](#-프로젝트-요약)

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


🔝 [프로젝트 요약으로 이동](#-프로젝트-요약)

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


🔝 [프로젝트 요약으로 이동](#-프로젝트-요약)

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


🔝 [프로젝트 요약으로 이동](#-프로젝트-요약)

---

## 🔐 보안/접근 관련 안내

- 본 저장소는 **일부 API 키, 민감한 경로 등은 제거**된 상태로 제공됩니다.
- 전체 실행 환경/설정이 필요하신 경우, 아래 연락처 또는 이력서에 명시된 인증 키를 통해 전체 접근 권한을 요청하실 수 있습니다.

📩 Contact: sungjun94@gmail.com  
🔑 Resume Key Access: 이력서 내 별도 안내 참고


🔝 [프로젝트 요약으로 이동](#-프로젝트-요약)

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


🔝 [프로젝트 요약으로 이동](#-프로젝트-요약)

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


🔝 [프로젝트 요약으로 이동](#-프로젝트-요약)

---

감사합니다 🙌  
이 포트폴리오를 통해 저의 **기술적 역량**과 **실행력**을 확인하실 수 있습니다.
