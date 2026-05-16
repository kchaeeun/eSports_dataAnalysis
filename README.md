# e스포츠 글로벌 흥행 요인 분석

> LCK와 베트남 e스포츠 커뮤니티 데이터를 활용한 글로벌 흥행 요인 데이터 분석 프로젝트

![Python](https://img.shields.io/badge/Python-3.10-blue)
![NLP](https://img.shields.io/badge/NLP-TextMining-orange)
![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-WebCrawling-green)
![NLTK](https://img.shields.io/badge/NLTK-KeywordAnalysis-red)
![Data Analytics](https://img.shields.io/badge/Data-Analytics-purple)

---

## 📌 프로젝트 개요

본 프로젝트는 글로벌 e스포츠 시장 성장 배경과 지역별 팬 문화 차이를 분석하기 위해 진행한 데이터 분석 프로젝트입니다.

특히 한국의 대표 e스포츠 리그인 **LCK(League of Legends Champions Korea)** 와
베트남 e스포츠 커뮤니티 데이터를 비교 분석하여,

- e스포츠 시장 성장 요인
- MZ세대의 게임 소비 문화
- 지역별 팬덤 특징
- 글로벌 흥행 요인

을 데이터 기반으로 도출하는 것을 목표로 했습니다.

---

## 🎯 프로젝트 목표

- e스포츠 시장 성장 원인 분석
- MZ세대 게임 문화와 소비 패턴 분석
- 한국과 베트남 팬덤 문화 비교
- 커뮤니티 기반 텍스트 데이터 분석
- 핵심 키워드 기반 글로벌 흥행 요인 도출

---

## 🧠 사용 기술

| 분야 | 기술 |
|---|---|
| Language | Python |
| Crawling | Selenium, BeautifulSoup |
| NLP | NLTK |
| Data Analysis | Pandas |
| Visualization | Matplotlib |
| Environment | Google Colab / Jupyter |

---

## 📂 프로젝트 구성

```text
1. e스포츠 시장 성장 분석
2. MZ세대 게임 문화 분석
3. 데이터 수집 및 텍스트 분석
4. 글로벌 흥행 요인 도출
```

---

## 📈 e스포츠 시장 성장 분석

### 분석 내용

- e스포츠 산업 성장 배경 조사
- 글로벌 리그 시장 규모 분석
- LCK 글로벌 인기 요인 분석
- 게임 산업과 스트리밍 문화 변화 분석

### 주요 인사이트

- e스포츠는 단순 게임이 아닌 콘텐츠 산업으로 확장
- Twitch · YouTube 기반 스트리밍 문화 성장
- 팬덤 중심 소비 문화 강화
- 국제 대회 중심의 글로벌 경쟁 구조 형성

---

## 🎮 MZ세대 게임 문화 분석

### 분석 내용

- 2030 세대 게임 이용 패턴 분석
- 게임 소비 문화 변화 분석
- 베트남 MZ세대 e스포츠 관심도 분석

### 주요 인사이트

- 게임을 단순 플레이가 아닌 ‘문화 콘텐츠’로 소비
- e스포츠 관람 및 커뮤니티 활동 증가
- SNS 기반 팬덤 참여 문화 활성화
- 팀 · 선수 중심 팬덤 형성 확대

---

## 🌏 베트남 e스포츠 팬덤 분석

### 분석 대상

- LCK Vietnam Facebook 커뮤니티
- 베트남 e스포츠 관련 게시글
- e스포츠 뉴스 및 커뮤니티 반응

### 분석 목적

한국 e스포츠 리그가 해외 팬덤에서 어떤 방식으로 소비되고 있는지 분석하고,
특히 베트남 팬층이 LCK에 열광하는 이유를 데이터 기반으로 파악했습니다.

---

## 🕸 데이터 수집

### 크롤링 도구

- Selenium
- BeautifulSoup
- Google Colab

### 수집 데이터

- LCK 관련 게시글
- 커뮤니티 댓글
- e스포츠 뉴스
- 팬 반응 데이터

### 크롤링 대상

- LCK Vietnam
- Under The Sea 커뮤니티
- e스포츠 관련 게시글

---

## 📝 텍스트 분석

### 사용 기법

- 자연어 처리(NLP)
- 토큰화(Tokenization)
- 단어 빈도 분석
- 핵심 키워드 추출

### 사용 라이브러리

```python
from nltk.tokenize import word_tokenize
from nltk.probability import FreqDist
```

### NLTK 사용 이유

- 영어 기반 텍스트 분석에 최적화
- 커뮤니티 댓글 데이터 분석 용이
- 단어 빈도 기반 핵심 키워드 추출 가능

---

## 🔍 핵심 키워드 분석

### 한국 커뮤니티 주요 키워드

| Keyword | 특징 |
|---|---|
| GEN | 젠지 관련 언급 다수 |
| T1 | 글로벌 인기 팀 |
| Faker | 대표 선수 팬덤 |
| LCK | 리그 자체 브랜드화 |

### 베트남 커뮤니티 주요 키워드

| Keyword | 특징 |
|---|---|
| T1 | 가장 높은 언급량 |
| Faker | 스타 플레이어 중심 팬덤 |
| Gen | 국제 대회 강팀 관심 |

---

## 📊 분석 결과

### 글로벌 흥행 요인

#### 1. 국제 대회의 확장

- MSI · Worlds 등 국제 대회를 통한 글로벌 팬층 확대
- 국가 대항전 형태의 경쟁 구도 형성

#### 2. 프랜차이즈 리그 구조

- 안정적인 팀 운영 환경 구축
- 장기적인 팬덤 형성 가능

#### 3. 리그 및 선수 브랜딩

- Faker와 같은 스타 플레이어 영향력
- 팀 중심 브랜드 가치 강화

#### 4. 커뮤니티 및 스트리밍 문화

- SNS · 실시간 채팅 기반 팬 참여 확대
- 글로벌 팬덤 간 상호작용 증가

---

## 💡 프로젝트 인사이트

이번 프로젝트를 통해 e스포츠 산업은 단순 게임 시장이 아니라,

- 콘텐츠 산업
- 스트리밍 산업
- 글로벌 팬덤 문화
- 디지털 커뮤니티

가 결합된 종합 엔터테인먼트 산업이라는 점을 확인할 수 있었습니다.

또한 국가별 팬덤 문화 차이를 데이터 기반으로 분석하며,
글로벌 시장에서는 단순 경기력뿐 아니라

- 커뮤니티 문화
- 선수 브랜딩
- 팬 경험

이 흥행에 큰 영향을 준다는 점을 도출했습니다.

---

## 🚀 기대 효과

- 글로벌 e스포츠 시장 이해도 향상
- 팬덤 문화 기반 데이터 분석 경험 확보
- NLP 기반 텍스트 마이닝 경험 습득
- 데이터 기반 콘텐츠 산업 분석 역량 강화

---

## 📄 프로젝트 정보

| 항목 | 내용 |
|---|---|
| 프로젝트명 | e스포츠 글로벌 흥행 요인 분석 |
| 유형 | 데이터 분석 프로젝트 |
| 분야 | NLP / 데이터 분석 / 크롤링 |
| 분석 대상 | LCK · 베트남 e스포츠 커뮤니티 |

---

## 🔗 Reference

- Riot Games
- LCK Official
- NLTK Documentation
- Selenium Documentation
- BeautifulSoup Documentation
