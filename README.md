# MLIC 강화학습 커리큘럼 로드맵

UNIST 대학원 MLIC 연구실의 신입생 및 인턴을 위한 1년 강화학습 커리큘럼 로드맵입니다.

## 📚 커리큘럼 개요

본 로드맵은 강화학습을 처음 시작하는 학생들이 1년 동안 체계적으로 학습하고 연구를 시작할 수 있도록 설계되었습니다.

### 5단계 학습 과정

1. **기초 공부 1** (1-2개월): 머신러닝 및 딥러닝 기초
2. **기초 공부 2** (3-4개월): 강화학습 이론 및 알고리즘
3. **기초 공부 3** (5-6개월): 고급 강화학습 및 실습
4. **연구 분야 탐색** (7-9개월): 최신 연구 동향 파악 및 관심 분야 선정
5. **연구 시작** (10-12개월): 독립적인 연구 프로젝트 수행

## 🌐 웹사이트 보기

### 로컬에서 실행

1. 저장소를 클론합니다:
```bash
git clone https://github.com/famouskawon/MLIC_crrui.git
cd MLIC_crrui
```

2. 웹 브라우저로 `index.html` 파일을 엽니다:
```bash
# macOS
open index.html

# Linux
xdg-open index.html

# Windows
start index.html
```

또는 간단한 HTTP 서버를 실행할 수 있습니다:
```bash
# Python 3
python -m http.server 8000

# Node.js
npx http-server
```

그런 다음 브라우저에서 `http://localhost:8000`을 방문합니다.

### GitHub Pages로 배포

1. GitHub 저장소의 Settings로 이동
2. 왼쪽 메뉴에서 "Pages" 선택
3. Source를 "Deploy from a branch"로 선택
4. Branch를 "main" 또는 해당 브랜치로 선택하고 저장
5. 몇 분 후 `https://famouskawon.github.io/MLIC_crrui/`에서 접속 가능

## 📁 파일 구조

```
MLIC_crrui/
├── index.html          # 메인 홈페이지
├── stage1.html         # 기초 공부 1 페이지
├── stage2.html         # 기초 공부 2 페이지
├── stage3.html         # 기초 공부 3 페이지
├── stage4.html         # 연구 분야 탐색 페이지
├── stage5.html         # 연구 시작 페이지
├── styles.css          # 통합 스타일시트
└── README.md           # 이 파일
```

## ✨ 주요 기능

- 📱 **반응형 디자인**: 모바일, 태블릿, 데스크톱 모두 지원
- 🎨 **현대적인 UI**: 그라디언트, 카드, 타임라인 등 시각적 요소
- 📚 **체계적인 구성**: 학습 목표, 강의 자료, 논문, 평가 기준 명확히 정리
- 🔗 **편리한 네비게이션**: 모든 페이지 간 쉬운 이동

## 🎯 각 단계별 내용

### 기초 공부 1 (1-2개월)
- Python, NumPy, Pandas 등 기본 도구
- 머신러닝 기초 개념
- 딥러닝 및 신경망
- PyTorch/TensorFlow 실습

### 기초 공부 2 (3-4개월)
- MDP, Bellman Equation
- Dynamic Programming
- Monte Carlo & TD Learning
- DQN 및 변형들

### 기초 공부 3 (5-6개월)
- Policy Gradient (REINFORCE, A3C)
- PPO, TRPO, SAC
- Model-Based RL
- 복잡한 환경 실습

### 연구 분야 탐색 (7-9개월)
- 최신 논문 읽기
- Multi-Agent, Offline, Meta-RL 등
- 논문 재현 및 분석
- Research Proposal 작성

### 연구 시작 (10-12개월)
- 연구 문제 정의
- 알고리즘 설계 및 구현
- 실험 수행 및 분석
- 학술 논문 작성

## 🤝 기여하기

개선 사항이나 제안이 있으시면 Issue를 열거나 Pull Request를 보내주세요.

## 📧 문의

UNIST MLIC Lab
- 웹사이트: [UNIST MLIC](https://mlic.unist.ac.kr)

## 📄 라이선스

이 프로젝트는 교육 목적으로 자유롭게 사용할 수 있습니다.

---

**© 2025 UNIST MLIC Lab. All rights reserved.**