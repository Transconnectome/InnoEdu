# 심리데이터 분석 I 강의계획서

> Inno-Edu 2031 | Method 모듈 | 신설 과목 N3
> 작성일: 2026-03-25

---

## 1. 교과목 기본 정보

| 항목 | 내용 |
|------|------|
| 교과목명 (국문) | 심리데이터 분석 I |
| 교과목명 (영문) | Psychological Data Analysis I |
| 학점/시수 | 3학점 / 주 3시간 |
| 대상 학년 | 2학년 |
| 개설 학기 | 2학기 |
| 소속 모듈 | Method (BMBM 4대 모듈) |
| 선수 과목 | E1 (심리통계학) |
| 담당 교수 | (미정) |

---

## 2. 교과목 개요 및 목표

### 교과목 개요

본 교과목은 E1(심리통계학)에서 습득한 통계 개념을 R/Python 코딩 기반 데이터 분석으로 확장하는 Method 모듈의 기술 심화 과목이다. R/RStudio 환경에서 tidyverse 기반 데이터 정제, ggplot2 시각화, 추론 통계(t-test, ANOVA, 회귀분석)를 수행하고, 고급 분석(다중회귀, 매개/조절, 요인분석 입문)으로 확장한다. Glasgow PsyTeachR(2024)의 Level 2 데이터 분석 교과를 벤치마크로 참조하여, 재현가능 연구 워크플로(R Markdown, OSF 사전등록)를 교과 전반의 핵심 원칙으로 관통시킨다. Use-Modify-Create 프레임워크를 적용하여 비전공자의 점진적 코딩 역량 구축을 도모한다.

### 학습 목표

본 교과목을 이수한 학생은 다음 역량을 달성한다:

1. **R 프로그래밍 역량**: R/RStudio 환경에서 tidyverse(dplyr, tidyr, ggplot2)를 활용한 데이터 정제, 변환, 시각화를 독립적으로 수행한다 (APA Goal 2).
2. **추론 통계 코딩**: t-test, ANOVA, 상관, 회귀분석을 R 코드로 실행하고, 효과크기와 신뢰구간을 포함한 결과를 해석한다 (APA Goal 2).
3. **고급 분석 기초**: 다중회귀, 매개/조절 분석, 요인분석의 기초를 R로 구현하고 결과를 해석한다 (APA Goal 2).
4. **재현가능 연구 실천**: R Markdown 기반 재현가능 보고서를 작성하고, OSF 사전등록 초안을 작성하여 오픈사이언스 원칙을 실천한다 (APA Goal 3).
5. **데이터 분석 포트폴리오**: 학기 전체 코딩 산출물을 포트폴리오로 종합하여 3학년 연구 참여 및 4학년 캡스톤의 분석 역량 기반을 형성한다 (APA Goal 5).

---

## 3. APA Guidelines 3.0 연계

| APA 학습목표 | 연계 내용 |
|-------------|----------|
| Goal 1: Knowledge Base | 심리학 데이터셋을 통한 심리학 연구 내용 이해 |
| Goal 2: Scientific Inquiry | R/Python 코딩, 추론 통계, 고급 분석, 데이터 시각화 |
| Goal 3: Ethical Responsibility | 재현가능 연구, 오픈사이언스 실천(OSF, 사전등록), 데이터 보호 |
| Goal 4: Communication | R Markdown 보고서, PBL 프로젝트 발표, 데이터 시각화 커뮤니케이션 |
| Goal 5: Professional Development | 데이터 분석 포트폴리오 구축, 연구 파이프라인 역량 형성 |

**Cross-Cutting Integrative Themes**: Scientific Inquiry(데이터 분석 기반 연구), Ethical Responsibility(재현가능 연구와 오픈사이언스)

---

## 4. 수업 운영 방식

| 방식 | 비율 | 설명 |
|------|------|------|
| 강의 | 30% | 통계 개념, 분석 원리, 재현가능 연구. 플립드 클래스룸 구조 — 사전 비디오 학습 + 개념 확인 (Playfoot, 2023 근거) |
| 코딩 실습 | 50% | R/tidyverse 기반 실시간 코딩. Use-Modify-Create 프레임워크 적용 — 예제 코드 이해(Use) → 수정(Modify) → 독립 작성(Create) |
| PBL | 20% | 4-5명 팀 프로젝트 — 공개 데이터셋 분석 프로젝트. SOLO 기반 형성적 평가 (B7 발견 5) |

**교수법 근거**: Glasgow PsyTeachR(2024) Level 2 수준. Schneider et al.(2025) PBL 2차 메타분석 ES=0.60. Freeman et al.(2014) 능동학습 0.47 SD 향상.

---

## 5. 주차별 수업 계획 (16주)

| 주차 | 주제 | 수업 내용 | 활동/과제 |
|------|------|----------|----------|
| 1 | 데이터 분석 워크플로우 개관 | 재현가능 연구의 원칙, 분석 파이프라인(수집→정제→분석→시각화→보고), 재현성 위기(Nosek et al., 2015) 소개 | [설문] SRA 사전 평가 + OSCI 사전 평가 |
| 2 | R/RStudio 환경 설정 | R/RStudio 설치(Posit Cloud 병행), R 기본 문법(변수, 벡터, 데이터프레임), learnr 인터랙티브 튜토리얼 | [실습] learnr 기반 R 기초 연습 (Use 단계) |
| 3 | R 기초 심화 | 조건문, 반복문, 함수 작성, R 패키지 설치/로드. Mahner et al.(2025) 코딩 10대 원칙 도입 | [과제] R 기초 코딩 과제 (Modify 단계) |
| 4 | 데이터 가져오기와 정제 (tidyverse) | dplyr(filter, select, mutate, summarize, group_by), tidyr(pivot_longer/wider), 파이프 연산자(%>%) | [실습] 심리학 데이터셋 정제 실습 (ds4psy 교재 참조) |
| 5 | 탐색적 데이터 분석 (EDA) — ggplot2 | ggplot2 문법 체계, 심리학 데이터 시각화(히스토그램, 산점도, 박스플롯), 시각화 원칙 | [과제] 심리학 데이터셋 EDA 보고서 (ggplot2) |
| 6 | 기술통계와 시각화 통합 | 중심경향, 분산, 정규성 검정, 효과크기 개념 복습. R 기반 기술통계 산출 + 시각화 통합 | [실습] 기술통계-시각화 통합 보고서 |
| 7 | t-test — R 실습 | 독립표본/대응표본 t-test, 효과크기(Cohen's d), 신뢰구간. R 코드 실행 + 결과 해석 | [과제] t-test 분석 보고서 (R Markdown 형식 첫 도입) |
| 8 | 중간고사 | R 코딩 + 통계 개념 통합 평가 (R Markdown 기반) | |
| 9 | ANOVA — R 실습 | 일원/이원 ANOVA, 사후 검정, 효과크기(eta-squared). R 코드 실행 + 결과 해석 | [실습] ANOVA 분석 과제 |
| 10 | 상관과 단순회귀 — R 실습 | Pearson/Spearman 상관, 단순 선형 회귀, 회귀 진단, R² 해석 | [과제] 회귀분석 보고서 (R Markdown) |
| 11 | 다중회귀와 매개/조절 분석 | 다중회귀 모형, 매개 분석(mediation), 조절 분석(moderation). R lavaan/processR 패키지 | [실습] 매개/조절 분석 실습 |
| 12 | 요인분석과 구조방정식 입문 | 탐색적 요인분석(EFA), 확인적 요인분석(CFA) 개념, R lavaan 패키지 기초. Thibault et al.(2024) "측정 이론" 핵심 기술 | [실습] 요인분석 실습 보고서 |
| 13 | 재현가능 연구와 R Markdown | R Markdown/Quarto 기반 재현가능 보고서 작성. Frank et al.(2025) Experimentology 모델. Korbmacher et al.(2023) 재현성 '혁명' | [실습] R Markdown 보고서 완성본 작성 |
| 14 | 오픈사이언스 도구와 공개 데이터셋 | OSF 프로젝트 생성, 사전등록 초안 작성. ABCD Study(Saragosa-Harris et al., 2022) 등 공개 데이터셋 활용 | [실습] OSF 사전등록 초안 + 공개 데이터셋 분석 |
| 15 | PBL 프로젝트 발표 | 4-5명 팀별 공개 데이터셋 분석 프로젝트 발표 + 구조화된 동료 피드백 | [발표] PBL 프로젝트 + 동료평가 루브릭 |
| 16 | 종합: 데이터 분석 포트폴리오 | 학기 전체 코딩 산출물 포트폴리오 정리 + 성찰 에세이. SRA/OSCI 사후 평가. 3학년 연구 참여 안내 | [과제] 포트폴리오 + 성찰 에세이 + SRA/OSCI 사후 |

---

## 6. 교재 및 참고문헌

### 주교재
- Navarro, D. (2022). *Learning Statistics with R/JASP*. CC BY-SA 4.0. (오픈 액세스)
- Field, A., Miles, J., & Field, Z. (2025). *Discovering Statistics Using R and JASP* (6th ed.). Sage.

### 부교재
- Neth, H. (2024). *Data Science for Psychologists (ds4psy)*. R 패키지 기반 오픈 교재. Konstanz 대학.
- Cetinkaya-Rundel, M., & Hardin, J. (2023). *Introduction to Modern Statistics* (2nd ed.). OpenIntro. (오픈 액세스)

### 참고 논문 (근거 매핑 기반)
- Glasgow PsyTeachR (2024). 학부 전 수준 R 기반 재현 가능 연구 교육 전환.
- Frank, M. C., et al. (2025). *Experimentology*. MIT Press.
- Nosek, B. A., et al. (2015). Estimating the reproducibility of psychological science. *Science, 349*(6251).
- Korbmacher, M., et al. (2023). The replication crisis has led to positive structural, procedural, and community changes. *Communications Psychology, 1*, 3.
- Saragosa-Harris, N. M., et al. (2022). A practical guide for researchers using the ABCD Study. *Developmental Cognitive Neuroscience, 55*, 101091.
- Mahner, P., et al. (2025). Ten simple rules for good research code. *PLOS Computational Biology*.
- Schneider, M., et al. (2025). PBL meta-analysis of meta-analyses. *Review of Educational Research*.
- Playfoot, D. (2023). Flipped classrooms in undergraduate psychology statistics. *Psychology Learning & Teaching*.
- Markant, D., & Galati, A. (2023). Open Science Concept Inventory (OSCI).
- Pownall, M., et al. (2023). Teaching open and reproducible scholarship. *Psychology Learning & Teaching, 22*(1), 3-35.

---

## 7. 평가 방법 및 기준

| 항목 | 비중 | 세부 내용 |
|------|------|----------|
| 출석 및 참여 | 5% | 수업 참여도, 실습 참여 |
| R 코딩 과제 (4회) | 25% | tidyverse 정제, ggplot2 시각화, t-test/ANOVA, 회귀분석 코딩 과제. R Markdown 형식 제출 |
| 중간고사 (R Markdown) | 15% | R 코딩 + 통계 개념 통합 평가. 재현가능 형태로 작성 |
| 매개/조절·요인분석 실습 보고서 | 10% | 고급 분석 R 코드 + 결과 해석 보고서 |
| R Markdown 재현가능 보고서 | 10% | 재현가능 보고서 작성 역량 평가. Frank et al.(2025) 품질 기준 참조 |
| PBL 프로젝트 | 20% | 제안서 5% + 최종 보고서 10% + 동료평가 5%. SOLO Taxonomy 기반 루브릭. 4-5명 팀 |
| 포트폴리오 + 성찰 에세이 | 15% | 학기 전체 코딩 산출물 종합 포트폴리오 + 성찰 에세이. Morreale et al.(2017) ePortfolio 원칙 참조 |

**사전-사후 측정 도구**: SRA(Garfield, 2003), OSCI(Markant & Galati, 2023), K-DOCS 단축형 20문항(Kaufman et al., 2012)

---

## 8. AI 사용 정책

### AI 도구 허용 범위
- **허용**: R 코딩 디버깅, 함수 검색, 오류 해결에 AI 도구 활용 가능. 단, 핵심 분석 로직은 학생이 직접 작성해야 한다.
- **제한**: 코딩 과제 제출물에 AI 도구 활용 내역을 R Markdown 문서 말미에 기술. AI가 생성한 코드를 그대로 제출하는 것은 금지.
- **금지**: 성찰 에세이에서 AI 생성 텍스트 직접 제출 금지. PBL 프로젝트 보고서의 결과 해석 및 논의 섹션은 학생이 직접 작성.

### 학술 무결성 기준
- 본 과목은 Stanford AIMES 프레임워크에서 **AI-Limited** 수준에 해당한다.
- 코딩 과제의 학술 무결성은 과정 중심 평가(코딩 과정 설명, R Markdown 주석)로 확보한다.
- Perkins et al.(2024/2025) AIAS v2의 5단계 프레임워크에 따라 과목 내 AI 활용 수준을 명시한다.

### AI 결과물 인용 방법
- AI 도구를 통해 작성된 코드는 주석으로 "# AI 보조 (ChatGPT, 2026): 디버깅 참조" 등으로 표기한다.
- 분석 결과 해석에 AI를 참조한 경우 R Markdown 보고서에 방법론적 주석으로 기술한다.

---

## 9. 수업 규정

### 출석 정책
- 총 수업 시수의 75% 이상 출석 필수 (서울대학교 학칙 준수).
- 3회 이상 무단 결석 시 F 학점 부여.
- 코딩 실습 수업은 실시간 참여가 핵심이므로, 대면 출석을 강력히 권장한다.

### 과제 제출 정책
- 모든 과제는 R Markdown(.Rmd) 또는 HTML 형태로 LMS를 통해 마감일 23:59까지 제출한다.
- 코드 실행 가능 상태(reproducible)로 제출. 실행 불가 시 감점.
- 지각 제출: 1일당 10% 감점, 최대 3일까지 허용.
- 학술적 부정행위 적발 시 해당 과제 0점 처리 및 학과 학술윤리위원회에 보고한다.

---

## 10. 장애 학생 지원 안내

서울대학교 장애학생지원센터(02-880-8787)와 연계하여 다음 지원을 제공한다:
- 시험 시간 연장 (1.5배)
- 코딩 실습 시 보조 인력 배치
- 화면 확대/음성 지원 소프트웨어 제공 (RStudio 접근성 설정)
- Posit Cloud 기반 원격 실습 환경 제공
- 대체 과제 형태 협의

장애 학생은 학기 초 2주 이내에 담당 교수에게 개별 면담을 요청하여 필요한 지원을 협의할 수 있다.

---

*강의계획서 작성: 2026-03-25 | Inno-Edu 2031 Step 7*
*근거 소스: N3_evidence.md, curriculum_master_plan.md, 06_synthesis.md*
