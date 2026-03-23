# 검색 프롬프트 모음

> Inno-Edu 2031 체계적 문헌연구를 위한 DB별·분기별 검색 전략
> 최종 업데이트: 2026-03-12

---

## 사용 가이드

본 문서는 600편 체계적 문헌연구의 7개 분기별로 최적화된 검색 프롬프트를 제공한다. 각 검색 전략은 다음을 포함한다:
- **주요 DB**: 해당 분기에 가장 적합한 학술 데이터베이스
- **구조화 검색식**: Boolean 연산자 기반 검색 쿼리
- **필터 조건**: 연도, 언어, 소스 유형 제한
- **보충 검색**: grey literature, forward/backward citation

### 공통 필터

| 필터 | 기본 설정 | 예외 |
|------|----------|------|
| 연도 | 2015-2026 | AI 관련: 2020-2026 / 기초이론: 제한 없음 |
| 언어 | 영어, 한국어 | — |
| 소스 유형 | 학술논문, 리뷰, 보고서, 프로그램 | — |
| 접근 가능성 | 서울대 도서관 접근 가능 소스 우선 | 오픈액세스 병행 |

---

## B1: BMBM 교과과정 설계

### B1.1 교과과정 개편 이론 (30편 목표)

#### PsycINFO / ERIC

```
검색식 1 (모듈형 설계):
("psychology curriculum" OR "psychology major" OR "psychology program")
AND ("reform" OR "redesign" OR "innovation" OR "transformation")
AND ("modular" OR "module" OR "competency-based" OR "outcome-based")
필터: 2015-2026, 영어, peer-reviewed

검색식 2 (역량기반 교육):
("competency-based education" OR "CBE" OR "learning outcomes")
AND ("psychology" OR "social science" OR "behavioral science")
AND ("undergraduate" OR "higher education")
필터: 2015-2026, 영어

검색식 3 (학제간 융합):
("interdisciplinary" OR "multidisciplinary" OR "transdisciplinary")
AND ("psychology" OR "neuroscience" OR "cognitive science")
AND ("curriculum" OR "program" OR "education")
필터: 2015-2026, 영어

검색식 4 (심리학 표준):
"APA Guidelines" AND ("undergraduate" OR "curriculum" OR "psychology major")
필터: 2013-2026, 영어
```

#### Google Scholar (보충)

```
"psychology curriculum reform" modular 2020..2026
"competency-based" "psychology education" undergraduate
"APA Guidelines 3.0" curriculum implementation
```

### B1.2 Brain 모듈 (25편 목표)

#### PsycINFO / PubMed

```
검색식 1 (인지신경과학 교육):
("cognitive neuroscience" OR "neuroscience")
AND ("education" OR "teaching" OR "curriculum" OR "course")
AND ("undergraduate" OR "college" OR "university")
필터: 2015-2026, 영어

검색식 2 (뇌영상 교육):
("neuroimaging" OR "fMRI" OR "EEG" OR "brain imaging")
AND ("education" OR "teaching" OR "training" OR "course")
AND ("undergraduate" OR "student")
필터: 2015-2026, 영어

검색식 3 (계산신경과학):
("computational neuroscience" OR "computational cognitive")
AND ("education" OR "course" OR "teaching" OR "curriculum")
필터: 2015-2026, 영어

검색식 4 (신경-심리 통합):
("mind brain education" OR "neuroeducation" OR "educational neuroscience")
AND ("curriculum" OR "program" OR "framework")
필터: 2015-2026, 영어
```

### B1.3 Mind 모듈 (20편 목표)

#### PsycINFO

```
검색식 1 (인지심리 교수법):
("cognitive psychology" OR "cognition")
AND ("teaching" OR "pedagogy" OR "education")
AND ("undergraduate" OR "course design")
필터: 2015-2026, 영어

검색식 2 (언어·지각 실습):
("perception" OR "language psychology" OR "psycholinguistics")
AND ("laboratory" OR "lab" OR "practical" OR "hands-on")
AND ("education" OR "teaching")
필터: 2015-2026, 영어

검색식 3 (철학-CS 융합):
("philosophy of mind" OR "consciousness")
AND ("computer science" OR "artificial intelligence" OR "cognitive science")
AND ("education" OR "curriculum" OR "interdisciplinary")
필터: 2015-2026, 영어
```

### B1.4 Behavior 모듈 (20편 목표)

#### PsycINFO

```
검색식 1 (사회·임상 실증):
("social psychology" OR "clinical psychology")
AND ("evidence-based" OR "empirical" OR "data-driven")
AND ("teaching" OR "education" OR "curriculum")
필터: 2015-2026, 영어

검색식 2 (발달 종단데이터):
("developmental psychology" OR "lifespan development")
AND ("longitudinal data" OR "longitudinal study")
AND ("teaching" OR "education" OR "visualization")
필터: 2015-2026, 영어

검색식 3 (조직·경제 빅데이터):
("organizational psychology" OR "industrial-organizational" OR "I-O psychology")
AND ("big data" OR "HR analytics" OR "people analytics" OR "data science")
필터: 2015-2026, 영어
```

### B1.5 Method 모듈 (15편 목표)

#### ERIC / PsycINFO

```
검색식 1 (심리통계 혁신):
("statistics education" OR "statistical reasoning")
AND ("psychology" OR "behavioral science")
AND ("innovation" OR "reform" OR "R programming" OR "Python")
필터: 2015-2026, 영어

검색식 2 (실험설계 개편):
("experimental design" OR "research methods")
AND ("digital" OR "online" OR "PsychoPy" OR "jsPsych")
AND ("psychology" OR "teaching")
필터: 2015-2026, 영어

검색식 3 (데이터분석 도구):
("data analysis tools" OR "statistical software")
AND ("psychology education" OR "behavioral science education")
AND ("R" OR "Python" OR "SPSS" OR "JASP")
필터: 2015-2026, 영어
```

---

## B2: AI·데이터 기반 연구 방법론

### B2.1 AI in Psychology Education (30편 목표)

#### PsycINFO / arXiv / IEEE

```
검색식 1 (LLM/GenAI 활용):
("large language model" OR "LLM" OR "ChatGPT" OR "GPT" OR "generative AI")
AND ("psychology" OR "behavioral science" OR "social science" OR "mental health")
필터: 2020-2026, 영어

검색식 2 (AI 리터러시):
("AI literacy" OR "artificial intelligence literacy" OR "AI competency")
AND ("psychology" OR "higher education" OR "undergraduate" OR "social science")
필터: 2020-2026, 영어

검색식 3 (AI 튜터링):
("intelligent tutoring" OR "AI tutor" OR "adaptive tutoring" OR "chatbot education")
AND ("psychology" OR "higher education" OR "STEM")
필터: 2018-2026, 영어

검색식 4 (AI 윤리):
("AI ethics" OR "responsible AI" OR "algorithmic bias" OR "AI fairness")
AND ("psychology" OR "behavioral science" OR "education")
필터: 2020-2026, 영어
```

### B2.2 데이터 사이언스 (25편 목표)

#### PsycINFO / Scopus

```
검색식 1 (데이터분석 교육과정):
("data science curriculum" OR "data science education" OR "data analytics education")
AND ("psychology" OR "social science" OR "behavioral science" OR "higher education")
필터: 2018-2026, 영어

검색식 2 (ML 응용):
("machine learning" OR "deep learning" OR "neural network")
AND ("psychology" OR "behavioral" OR "cognitive")
AND ("application" OR "education" OR "teaching")
필터: 2018-2026, 영어

검색식 3 (빅데이터 방법):
("big data" OR "computational social science")
AND ("psychology" OR "behavioral science")
AND ("method" OR "methodology" OR "approach")
필터: 2015-2026, 영어

검색식 4 (오픈사이언스):
("open science" OR "reproducibility" OR "replication crisis" OR "preregistration")
AND ("psychology" OR "behavioral science")
필터: 2015-2026, 영어
```

### B2.3 Python/R 실습 교육 (20편 목표)

#### ERIC / PsycINFO

```
검색식 1 (Python 심리학):
("Python" OR "Python programming")
AND ("psychology" OR "behavioral science" OR "statistics" OR "data analysis")
AND ("education" OR "teaching" OR "course" OR "curriculum")
필터: 2015-2026, 영어

검색식 2 (R 통계교육):
("R programming" OR "R software" OR "RStudio" OR "tidyverse")
AND ("statistics education" OR "data analysis" OR "psychology")
필터: 2015-2026, 영어

검색식 3 (비전공자 코딩):
("coding" OR "programming") AND ("non-major" OR "beginners" OR "novice")
AND ("social science" OR "psychology" OR "higher education")
필터: 2015-2026, 영어
```

### B2.4 연구 파이프라인 AI 통합 (25편 목표)

#### PsycINFO / arXiv

```
검색식 1 (문헌검색 자동화):
("automated literature review" OR "AI literature search" OR "systematic review automation")
AND ("psychology" OR "social science" OR "research")
필터: 2020-2026, 영어

검색식 2 (데이터수집 자동화):
("automated data collection" OR "digital phenotyping" OR "experience sampling")
AND ("psychology" OR "behavioral science")
필터: 2018-2026, 영어

검색식 3 (AI 분석·시각화):
("AI-assisted analysis" OR "automated analysis" OR "data visualization")
AND ("psychology" OR "behavioral" OR "research")
필터: 2020-2026, 영어

검색식 4 (논문작성 AI):
("AI writing" OR "AI-assisted writing" OR "automated scientific writing")
AND ("academic" OR "research" OR "psychology")
필터: 2020-2026, 영어
```

---

## B3: PBL 및 수업방법 혁신

### B3.1 PBL in STEM/Social Science (30편 목표)

#### ERIC / PsycINFO

```
검색식 1 (PBL 메타분석):
("problem-based learning" OR "project-based learning" OR "PBL")
AND ("meta-analysis" OR "systematic review" OR "effectiveness")
AND ("higher education" OR "university" OR "college")
필터: 2015-2026, 영어

검색식 2 (심리학 PBL 사례):
("problem-based learning" OR "project-based learning" OR "PBL")
AND ("psychology" OR "behavioral science" OR "social science")
필터: 2015-2026, 영어

검색식 3 (CURE — Course-based Undergraduate Research):
("CURE" OR "course-based undergraduate research")
AND ("psychology" OR "STEM" OR "science education")
필터: 2015-2026, 영어

검색식 4 (PBL 평가):
("PBL" OR "problem-based learning")
AND ("assessment" OR "evaluation" OR "rubric" OR "outcomes")
AND ("higher education")
필터: 2015-2026, 영어
```

### B3.2 Active Learning (25편 목표)

#### ERIC

```
검색식 1 (효과 연구):
("active learning") AND ("meta-analysis" OR "effectiveness" OR "outcomes")
AND ("higher education" OR "STEM" OR "science")
필터: 2014-2026, 영어

검색식 2 (Flipped Classroom):
("flipped classroom" OR "inverted classroom" OR "flipped learning")
AND ("psychology" OR "social science" OR "higher education")
필터: 2015-2026, 영어

검색식 3 (Team-Based Learning):
("team-based learning" OR "TBL" OR "collaborative learning")
AND ("higher education" OR "psychology" OR "health science")
필터: 2015-2026, 영어
```

### B3.3 AI 강화 교수법 (20편 목표)

#### ERIC / IEEE

```
검색식 1 (적응형 학습):
("adaptive learning" OR "personalized learning" OR "intelligent tutoring")
AND ("higher education" OR "psychology" OR "science")
필터: 2018-2026, 영어

검색식 2 (Learning Analytics):
("learning analytics" OR "educational data mining")
AND ("higher education" OR "psychology" OR "intervention")
필터: 2015-2026, 영어

검색식 3 (AI Teaching):
("AI-enhanced teaching" OR "AI in teaching" OR "AI classroom")
AND ("higher education" OR "pedagogy")
필터: 2020-2026, 영어
```

### B3.4 창의적 학습 환경 (15편 목표)

#### ERIC

```
검색식 1 (몰입도):
("student engagement" OR "immersive learning" OR "flow state")
AND ("higher education" OR "psychology" OR "active learning")
필터: 2015-2026, 영어

검색식 2 (Learning Assistants):
("learning assistant" OR "peer instruction" OR "supplemental instruction")
AND ("STEM" OR "science" OR "higher education")
필터: 2015-2026, 영어

검색식 3 (Reflective Practice):
("reflective practice" OR "reflective learning" OR "metacognition")
AND ("higher education" OR "psychology" OR "professional development")
필터: 2015-2026, 영어
```

---

## B4: 학부생 연구역량 파이프라인

### B4.1 URP 모델 (25편 목표)

#### ERIC / CUR Publications

```
검색식 1 (URP 설계·효과):
("undergraduate research" OR "URP" OR "undergraduate research program")
AND ("design" OR "effectiveness" OR "outcomes" OR "impact")
필터: 2010-2026, 영어

검색식 2 (연구 매칭):
("research mentoring" OR "faculty-student research" OR "research matching")
AND ("undergraduate" OR "psychology" OR "STEM")
필터: 2015-2026, 영어

검색식 3 (연구 동기):
("research self-efficacy" OR "research motivation" OR "research identity")
AND ("undergraduate" OR "psychology")
필터: 2015-2026, 영어
```

### B4.2 졸업논문 혁신 (20편 목표)

#### ERIC

```
검색식 1 (캡스톤):
("capstone" OR "senior thesis" OR "capstone project")
AND ("psychology" OR "social science" OR "design")
AND ("undergraduate" OR "higher education")
필터: 2015-2026, 영어

검색식 2 (다중 트랙):
("multi-track" OR "alternative assessment" OR "portfolio")
AND ("thesis" OR "capstone" OR "graduation requirement")
AND ("higher education")
필터: 2015-2026, 영어
```

### B4.3 연구 윤리·IRB (15편 목표)

#### PsycINFO / ERIC

```
검색식 1 (윤리 교육):
("research ethics education" OR "research integrity" OR "responsible conduct")
AND ("undergraduate" OR "student" OR "training")
필터: 2015-2026, 영어

검색식 2 (IRB 훈련):
("IRB" OR "institutional review board" OR "ethics review")
AND ("training" OR "education" OR "undergraduate")
필터: 2015-2026, 영어

검색식 3 (데이터 보호):
("data protection" OR "data privacy" OR "GDPR")
AND ("research" OR "education" OR "training")
AND ("psychology" OR "social science")
필터: 2018-2026, 영어
```

### B4.4 학술대회·논문 투고 (20편 목표)

#### ERIC / PsycINFO

```
검색식 1 (학부생 학술 발표):
("undergraduate conference" OR "student research presentation" OR "poster presentation")
AND ("psychology" OR "social science" OR "effectiveness")
필터: 2015-2026, 영어

검색식 2 (학술 글쓰기):
("academic writing" OR "scientific writing" OR "writing instruction")
AND ("psychology" OR "undergraduate" OR "APA style")
필터: 2015-2026, 영어
```

---

## B5: 교수역량 강화

### B5.1 AI Teaching 역량 (25편 목표)

#### ERIC / Higher Education Journals

```
검색식 1 (AI Bootcamp):
("AI bootcamp" OR "AI training" OR "AI workshop")
AND ("faculty" OR "professor" OR "instructor" OR "teacher")
AND ("higher education")
필터: 2020-2026, 영어

검색식 2 (교수 AI 리터러시):
("faculty" OR "instructor") AND ("AI literacy" OR "AI competency" OR "AI readiness")
AND ("higher education")
필터: 2020-2026, 영어

검색식 3 (AI 수업 설계):
("AI" OR "artificial intelligence") AND ("course design" OR "curriculum design" OR "syllabus")
AND ("faculty" OR "instructor") AND ("higher education")
필터: 2020-2026, 영어
```

### B5.2 Teaching Innovation Pods (20편 목표)

#### ERIC

```
검색식 1 (FLC):
("faculty learning community" OR "FLC" OR "professional learning community")
AND ("higher education" OR "university")
필터: 2004-2026, 영어

검색식 2 (Teaching Innovation):
("teaching innovation" OR "pedagogical innovation" OR "teaching community")
AND ("higher education" OR "faculty development")
필터: 2015-2026, 영어
```

### B5.3 심리학 교수법 전문성 (15편 목표)

#### PsycINFO / Teaching of Psychology

```
검색식 1 (SoTL):
("scholarship of teaching and learning" OR "SoTL")
AND ("psychology" OR "higher education")
필터: 2010-2026, 영어

검색식 2 (영역별 교수법):
("discipline-specific pedagogy" OR "teaching psychology")
AND ("AI" OR "technology" OR "data science")
필터: 2018-2026, 영어
```

### B5.4 CTL 모델 (10편 목표)

#### ERIC / Institutional Sources

```
검색식 1:
("center for teaching and learning" OR "CTL" OR "teaching center")
AND ("model" OR "effectiveness" OR "institutional support")
AND ("higher education")
필터: 2015-2026, 영어
```

#### Institutional Web Search

```
site:ctl.stanford.edu AI education
site:bokcenter.harvard.edu teaching AI
site:tll.mit.edu teaching innovation
"center for teaching" "AI integration" university
```

---

## B6: 글로벌 벤치마크 및 정책

### B6.1 글로벌 선도 대학 (30편 목표)

#### Google Scholar / Institutional Sources

```
검색식 1 (Stanford AIMES):
"Stanford AIMES" OR ("Stanford" AND "AI education" AND "initiative")
필터: 2020-2026, 영어

검색식 2 (Harvard Bok):
"Harvard Bok Center" AND ("AI" OR "artificial intelligence" OR "teaching")
필터: 2020-2026, 영어

검색식 3 (MIT DAILy):
"MIT DAILy" OR ("MIT" AND "AI education" AND "creative")
필터: 2020-2026, 영어

검색식 4 (Oxford):
"Oxford" AND ("computational psychology" OR "summer school" OR "psychology education")
필터: 2020-2026, 영어

검색식 5 (NUS):
"NUS" AND ("ChatGPT" OR "LLM") AND "psychology"
필터: 2023-2026, 영어
```

#### Institutional Web Sources

```
site:stanford.edu AIMES AI education psychology
site:harvard.edu "Bok Center" AI teaching framework
site:mit.edu DAILy AI education
site:ox.ac.uk computational psychology summer
site:nus.edu.sg psychology AI ChatGPT
```

### B6.2 APA Guidelines 3.0 (20편 목표)

#### PsycINFO

```
검색식 1 (APA 3.0):
"APA Guidelines" AND ("3.0" OR "2023" OR "undergraduate psychology major")
필터: 2023-2026, 영어

검색식 2 (APA 학습목표):
("APA" AND "learning goals" OR "learning outcomes")
AND ("psychology" AND "undergraduate")
필터: 2013-2026, 영어

검색식 3 (Cross-Cutting Themes):
"APA" AND ("cross-cutting" OR "integrative themes" OR "psychological literacy")
AND ("curriculum" OR "education")
필터: 2013-2026, 영어
```

### B6.3 아시아 대학 혁신 (15편 목표)

#### Scopus / Web of Science

```
검색식 1 (아시아 전반):
("Asia" OR "Japan" OR "China" OR "Singapore" OR "Korea" OR "Taiwan")
AND ("psychology education" OR "curriculum innovation" OR "AI education")
AND ("university" OR "higher education")
필터: 2018-2026, 영어

검색식 2 (한국):
("Korea" OR "Korean")
AND ("psychology education" OR "curriculum" OR "higher education innovation")
필터: 2015-2026, 영어/한국어
```

#### 한국어 검색 (KCI / RISS)

```
("심리학 교육" OR "심리학과 교과과정") AND ("개편" OR "혁신" OR "AI")
("고등교육" OR "대학교육") AND ("AI" OR "인공지능") AND ("심리학")
("교과과정 개편") AND ("대학" OR "학부") AND ("심리" OR "사회과학")
```

### B6.4 고등교육 정책 (15편 목표)

#### ERIC / 정부 출판물

```
검색식 1 (한국 교육부):
("Korea" OR "Korean") AND ("higher education policy" OR "education reform" OR "curriculum policy")
AND ("innovation" OR "AI" OR "digital")
필터: 2020-2026, 영어/한국어

검색식 2 (서울대):
("Seoul National University" OR "SNU")
AND ("curriculum" OR "education" OR "innovation" OR "reform")
필터: 2015-2026, 영어/한국어

검색식 3 (유사 사업):
("Inno-Edu" OR "education innovation project" OR "curriculum innovation grant")
AND ("Korea" OR "university" OR "higher education")
필터: 2020-2026, 영어/한국어
```

#### 한국어 검색 (KCI / RISS / 교육부)

```
"Inno-Edu" OR "이노에듀" OR "창의교육프로젝트"
"서울대" AND ("교과과정" OR "교육혁신")
"교육부" AND ("고등교육" OR "대학교육") AND ("혁신" OR "AI")
"대학 혁신" AND ("교과과정" OR "커리큘럼") AND ("사회과학" OR "심리학")
```

---

## B7: 측정·평가·거버넌스

### B7.1 학습 성과 측정 (25편 목표)

#### PsycINFO / ERIC

```
검색식 1 (SRA):
("Statistical Reasoning Assessment" OR "SRA") AND ("psychology" OR "statistics education")
필터: 1990-2026, 영어

검색식 2 (SOLO Taxonomy):
"SOLO Taxonomy" AND ("higher education" OR "assessment" OR "learning quality")
필터: 2000-2026, 영어

검색식 3 (AI Literacy Scale):
("AI literacy" AND ("scale" OR "measure" OR "assessment" OR "instrument"))
필터: 2019-2026, 영어

검색식 4 (창의성):
("creativity" AND ("rubric" OR "assessment" OR "CREWS"))
AND ("education" OR "higher education")
필터: 2015-2026, 영어
```

### B7.2 프로그램 평가 (20편 목표)

#### ERIC

```
검색식 1 (교과과정 효과):
("curriculum evaluation" OR "program evaluation" OR "curriculum effectiveness")
AND ("psychology" OR "higher education" OR "STEM")
필터: 2015-2026, 영어

검색식 2 (PBL 성과):
("PBL" OR "problem-based learning") AND ("assessment" OR "evaluation" OR "outcomes")
AND ("higher education")
필터: 2015-2026, 영어
```

### B7.3 교육 거버넌스 (15편 목표)

#### ERIC / Higher Education Journals

```
검색식 1 (교육혁신위원회):
("education committee" OR "curriculum committee" OR "innovation council")
AND ("governance" OR "higher education" OR "university")
필터: 2015-2026, 영어

검색식 2 (AI 거버넌스):
("AI governance" OR "AI policy") AND ("higher education" OR "university")
필터: 2020-2026, 영어

검색식 3 (학생 참여):
("student voice" OR "student governance" OR "student participation")
AND ("curriculum" OR "education governance" OR "higher education")
필터: 2015-2026, 영어
```

### B7.4 AI 정책·학술 무결성 (10편 목표)

#### ERIC / Google Scholar

```
검색식 1 (대학 AI 정책):
("AI policy" OR "artificial intelligence policy")
AND ("university" OR "higher education" OR "institution")
필터: 2022-2026, 영어

검색식 2 (학술 무결성):
("academic integrity" OR "academic honesty" OR "plagiarism")
AND ("AI" OR "ChatGPT" OR "generative AI")
AND ("higher education" OR "university")
필터: 2022-2026, 영어
```

---

## 보충 검색 전략

### Forward/Backward Citation

예비 60편 소스 중 핵심 소스(Tier 1, quality:core)를 기점으로:

1. **Backward citation**: 참고문헌 목록에서 관련 소스 식별
2. **Forward citation**: Google Scholar "Cited by" 기능으로 후속 연구 추적
3. **관련 논문 추천**: Google Scholar "Related articles", Semantic Scholar 추천

#### 핵심 추적 대상 소스

| 소스 | Forward Citation 우선순위 |
|------|-------------------------|
| S01 (APA Guidelines 3.0) | APA 3.0 인용 논문 → B6.2 |
| S20 (Nosek 재현성) | 재현성 후속 연구 → B2.2.4 |
| S28 (Freeman Active Learning) | Active learning 후속 메타분석 → B3.2 |
| S35 (Lopatto URP) | URP 효과 후속 연구 → B4.1 |
| S44 (Cox FLC) | FLC 응용 연구 → B5.2 |

### Grey Literature 검색

```
# 기관 보고서
site:apa.org "guidelines" OR "education" OR "curriculum"
site:psychologicalscience.org "education" OR "teaching" OR "undergraduate"
site:cur.org "undergraduate research"
site:unesco.org "AI" AND "higher education"
site:oecd.org "AI" AND "education"

# 프로그램 웹사이트
site:stanford.edu "psychology" AND ("AI" OR "curriculum" OR "education")
site:harvard.edu "psychology" AND ("AI" OR "curriculum" OR "teaching")
site:mit.edu "brain" AND ("cognitive" OR "education" OR "AI")

# 교육부/정부
site:moe.go.kr "대학" AND ("혁신" OR "AI" OR "교과과정")
site:snu.ac.kr "교과과정" OR "교육혁신"
```

### 한국어 전용 검색 (RISS / KCI)

```
# RISS
("심리학" OR "심리학과") AND ("교과과정" OR "커리큘럼") AND ("개편" OR "혁신")
("AI" OR "인공지능") AND ("대학교육" OR "고등교육") AND ("심리" OR "사회과학")
("PBL" OR "문제기반학습") AND ("대학" OR "고등교육")
("학부생 연구" OR "학부 연구") AND ("심리학" OR "효과")
("교수 개발" OR "교수법 혁신") AND ("AI" OR "디지털")

# KCI
("심리학 교육" OR "심리학 교과과정") AND ("혁신" OR "개편" OR "AI")
("데이터 사이언스" OR "데이터분석") AND ("교육" OR "교과과정")
("능동적 학습" OR "프로젝트 기반") AND ("대학교육")
```

---

## Phase별 검색 우선순위

### P0: 예비연구 (60편)

이미 식별된 60편을 처리. 추가 검색 불요.

### P1: 핵심문헌 (200편)

| 우선순위 | 분기 | 검색식 | 목표 |
|----------|------|--------|------|
| 1 | B1 | 검색식 1-4 (B1.1) | 35편 |
| 1 | B2 | 검색식 1-4 (B2.1-B2.2) | 30편 |
| 2 | B3 | 검색식 1-3 (B3.1-B3.2) | 30편 |
| 2 | B6 | 검색식 1-5 (B6.1) + B6.2 | 30편 |
| 3 | B4 | 검색식 1-3 (B4.1-B4.2) | 25편 |
| 3 | B5 | 검색식 1-2 (B5.1-B5.2) | 25편 |
| 3 | B7 | 검색식 1-4 (B7.1) | 25편 |

### P2: 확장조사 (200편)

P1 결과의 커버리지 분석 후, 부족한 하위분기 중심으로 검색 확대.

### P3: 갭필·심화 (140편)

- 리프 카테고리 중 1편 미만인 영역 집중
- 2025-2026 최신 출판물 우선
- Forward/backward citation 집중 수행
