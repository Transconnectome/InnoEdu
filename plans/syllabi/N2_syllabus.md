# 심리과학을 위한 인공지능 강의계획서

> Inno-Edu 2031 | Method 모듈 | 신설 과목 N2
> 작성일: 2026-03-25

---

## 1. 교과목 기본 정보

| 항목 | 내용 |
|------|------|
| 교과목명 (국문) | 심리과학을 위한 인공지능 |
| 교과목명 (영문) | Artificial Intelligence for Psychological Science |
| 학점/시수 | 3학점 / 주 3시간 |
| 대상 학년 | 2학년 |
| 개설 학기 | 2학기 |
| 소속 모듈 | Method (BMBM 4대 모듈) |
| 선수 과목 | E1 (심리통계학) 권장 |
| 담당 교수 | (미정) |

---

## 2. 교과목 개요 및 목표

### 교과목 개요

본 교과목은 심리학 연구에서 AI/ML/NLP 기법을 활용하는 역량을 체계적으로 배양하기 위해 설계되었다. Python 프로그래밍 기초(변수, 자료구조, Pandas/NumPy)에서 출발하여 지도학습(분류/회귀), 비지도학습(군집분석/차원축소), NLP(텍스트 분석/감성분석)까지 확장하며, 이를 Brain-Mind-Behavior 7개 심리학 영역에 적용하는 실습을 수행한다. Ma et al.(2025) 메타분석에서 확인된 바와 같이, 모든 AI 도구 활용은 구조화된 scaffolding 하에 안내된 사용(instructed use) 원칙을 따른다. AI 윤리(WEIRD 편향, 공정성, 해석가능성)를 독립 주제이자 교과 전반에 내재화하여, 비판적 AI 활용 역량을 배양한다.

### 학습 목표

본 교과목을 이수한 학생은 다음 역량을 달성한다:

1. **Python 프로그래밍 기초**: Python 변수, 자료구조, 함수, Pandas/NumPy 데이터 처리 역량을 습득하여 심리학 데이터를 독립적으로 전처리한다 (APA Goal 2).
2. **ML 기법 적용**: 지도학습(분류/회귀)과 비지도학습(군집분석/차원축소)을 심리학 데이터에 적용하고, 교차 검증을 통한 모델 평가를 수행한다 (APA Goal 2).
3. **NLP 분석 역량**: 텍스트 전처리, 감성분석, 주제 모델링을 소셜미디어/설문 텍스트 데이터에 적용한다 (APA Goal 2).
4. **BMBM 영역별 AI 응용**: Brain(뇌영상 ML), Mind(인지 모델링), Behavior(임상/발달 AI)에 AI 기법을 적용하는 사례를 이해한다 (APA Goal 1).
5. **AI 윤리적 활용**: WEIRD 편향, 알고리즘 공정성, 해석가능성 등 AI 윤리 쟁점을 비판적으로 분석하고, 윤리적 AI 연구 실천 원칙을 적용한다 (APA Goal 3).

---

## 3. APA Guidelines 3.0 연계

| APA 학습목표 | 연계 내용 |
|-------------|----------|
| Goal 1: Knowledge Base | Brain/Mind/Behavior 각 영역에서 AI 적용 사례 이해, 심리학-AI 양방향 통합 |
| Goal 2: Scientific Inquiry | Python 코딩, ML/NLP 분석, 모델 평가, 재현 가능 분석 파이프라인 |
| Goal 3: Ethical Responsibility | WEIRD 편향, 알고리즘 공정성, AI 윤리 교과 내재화, 한국 AI 윤리 가이드라인 |
| Goal 4: Communication | PBL 프로젝트 발표, Jupyter Notebook 기반 분석 보고서 |
| Goal 5: Professional Development | AI 심리학의 미래 전망, 대학원/진로 연계 |

**Cross-Cutting Integrative Themes**: Scientific Inquiry(AI 기반 연구 방법), Ethical Responsibility(AI 윤리 내재화), Psychological Literacy(7개 영역별 AI 활용)

---

## 4. 수업 운영 방식

| 방식 | 비율 | 설명 |
|------|------|------|
| 강의 | 40% | AI/ML/NLP 이론, 심리학 연계 개념, AI 윤리. 플립드 구조 적용 — 사전 비디오 학습 + 개념 확인 |
| 코딩 실습 | 40% | Python/Jupyter Notebook 기반 실시간 코딩. Mahner et al.(2025)의 코딩 10대 원칙(변경 추적, 코드 테스트, 코드 리뷰) 적용 |
| PBL | 20% | 4-5명 팀 프로젝트 — BMBM 영역별 AI 응용 프로젝트. Zhang & Ma(2023) 메타분석 최적 파라미터(4-5명, 9-18주) 적용 |

**교수법 근거**: Playfoot(2023) 심리학 통계 플립드 클래스룸에서 유의미하게 높은 성적 확인. Schneider et al.(2025) PBL 2차 메타분석 ES=0.60.

---

## 5. 주차별 수업 계획 (16주)

| 주차 | 주제 | 수업 내용 | 활동/과제 |
|------|------|----------|----------|
| 1 | AI와 심리학 — 역사, 현재, 미래 | AI-심리학 관계 개관, Cushman(2024) ML/NLP 확산 추세, APA(2024) AI 역량 3대 도메인 | [사전 설문] AI 리터러시 사전 평가 (Long & Magerko, 2020 기반) |
| 2 | Python 기초 (1) | 변수, 자료형, 조건문, 반복문. Dalmaijer et al.(2024) *Python for Experimental Psychologists* 참조 | [실습] Python 기초 코딩 (인터랙티브 OER 활용) |
| 3 | Python 기초 (2) | 함수, 모듈, Pandas 데이터프레임, NumPy 배열. 코딩 10대 원칙(Mahner et al., 2025) 도입 | [과제] 심리학 데이터셋 전처리 (Pandas) |
| 4 | Python 데이터 시각화 | Matplotlib, Seaborn 활용 시각화, 심리학 데이터 탐색적 분석 | [실습] 성격 5요인 데이터 시각화 |
| 5 | 지도학습 I — 분류 | K-NN, 의사결정트리, 로지스틱 회귀. 심리학 데이터 기반 분류 (성격 유형, 정신건강 위험 예측) | [실습] scikit-learn 분류 실습 |
| 6 | 지도학습 II — 회귀와 모델 평가 | 선형/다중 회귀, 교차 검증, 과적합 시연. Nosek et al.(2015) 재현성과 과적합의 연결 교육 | [과제] 모델 평가 리포트 (교차 검증 결과 해석) |
| 7 | 비지도학습 — 군집분석, 차원축소 | K-means, 계층적 군집분석, PCA, t-SNE. 성격/태도 데이터 잠재 구조 발견 | [실습] Big Five 데이터 PCA/군집분석 + 시각화 |
| 8 | 중간고사 | 코딩 실습 + 개념 평가 (Jupyter Notebook 기반) | |
| 9 | NLP 기초 (1) — 텍스트 분석 | 텍스트 전처리, TF-IDF, 감성분석. P1-B2-013 NLP 행동과학 종합 리뷰 참조 | [실습] 소셜미디어 텍스트 감성분석 |
| 10 | NLP 기초 (2) — 주제 모델링과 LLM | 주제 모델링(LDA), LLM 기반 텍스트 분류. P3-S010 LLM 최소 프로그래밍 구현 참조 | [실습] 심리학 논문 초록 주제 모델링 |
| 11 | **WEIRD 편향과 GPTology** | Abdurahman et al.(2024) LLM WEIRD 편향(142% 동의 확률 증가), GPTology 경고. 한국 맥락 문화적 특수성 | [토론] LLM을 인간 피험자 대체물로 사용할 수 있는가? |
| 12 | Brain 모듈 연계 — 뇌영상 데이터와 ML | fMRI/EEG 데이터 구조, ML 기반 뇌영상 분류, Neuromatch Academy 참조 | [실습] 공개 EEG 데이터 ML 분류 |
| 13 | Behavior 모듈 연계 — 임상/발달 AI | ML + 디지털 측정 심리건강 평가, 디지털 표현형, 종단 데이터 AI 분석. P3-S016 웨어러블 센싱 동향 | [사례분석] 임상/발달 AI 적용 사례 보고서 |
| 14 | Mind 모듈 연계 — 인지 모델링과 AI | 계산 인지 모델, 베이지안 모델링, AI-인지과학 양방향 통합. Lake & Gureckis(NYU CCM, 2024) 참조 | [실습] 의사결정 모델링 미니 프로젝트 |
| 15 | AI 윤리·편향 종합 + 연구 파이프라인 AI 통합 | 알고리즘 편향 유형(Baker & Hawn, 2022), 공정성 지표, XAI, 교육부 AI 윤리 가이드라인(2024). AI 보조 연구 파이프라인 설계 | [과제] AI 윤리 분석 에세이 |
| 16 | PBL 프로젝트 발표 + 종합 | 팀 프로젝트 최종 발표, 동료 피드백, 학기 종합, AI 리터러시 사후 평가 | [발표] PBL 프로젝트 + [설문] AI 리터러시 사후 평가 |

---

## 6. 교재 및 참고문헌

### 주교재
- Dalmaijer, E. S., Van der Stigchel, S., & Mathot, S. (2024). *Python for Experimental Psychologists* (2nd ed.). Cambridge University Press.
- 강의 노트 및 Jupyter Notebook 교재 (교수자 제작)

### 부교재
- Mahner, P., et al. (2025). Ten simple rules for good research code. *PLOS Computational Biology*.
- Bainbridge, W. A. (2024). *Big Data in the Psychological Sciences*. APA Books.

### 참고 논문 (근거 매핑 기반)
- Ma, S., Lei, L., & Luo, H. (2025). The effect of generative AI on learning outcomes: A meta-analysis. *Educational Research Review*.
- Cushman, F. (2024). Computational approaches to social psychology. *Annual Review of Psychology, 75*, 199-225.
- Long, D., & Magerko, B. (2020). What is AI literacy? Competencies and design considerations. *CHI 2020*.
- Abdurahman, S., et al. (2024). Perils and opportunities in using LLMs in psychological research. *American Psychologist*.
- Nosek, B. A., et al. (2015). Estimating the reproducibility of psychological science. *Science, 349*(6251), aac4716.
- Baker, R. S., & Hawn, A. (2022). Algorithmic bias in education. *International Journal of Artificial Intelligence in Education, 32*, 1052-1092.
- P1-B2-013: NLP의 행동과학 텍스트 데이터 분석 종합 리뷰. *Nature Reviews Psychology*.
- P1-B2-014: 1991-2023 심리학 NLP 4,909편 서지분석.
- Lake, B. M., & Gureckis, T. M. (2024). Computational cognitive modeling course. NYU CCM.
- Schneider, M., et al. (2025). PBL meta-analysis of meta-analyses. *Review of Educational Research*.

---

## 7. 평가 방법 및 기준

| 항목 | 비중 | 세부 내용 |
|------|------|----------|
| 출석 및 참여 | 5% | 수업 참여도, 토론 기여도 |
| 코딩 실습 과제 (4회) | 25% | Python 기초, 지도학습, 비지도학습, NLP 코딩 과제. Jupyter Notebook 기반 자동/수동 채점 병행 |
| 중간고사 (Jupyter Notebook) | 15% | Python 코딩 + ML 개념 통합 평가 |
| 모델 평가 리포트 | 10% | 교차 검증 결과 해석, 과적합 분석, 재현 가능 분석 원칙 |
| AI 윤리 분석 에세이 | 10% | WEIRD 편향, 알고리즘 공정성, 심리학 AI 윤리 비판적 분석 (APA Goal 3) |
| PBL 프로젝트 | 25% | 제안서 5% + 중간 발표 5% + 최종 보고서 10% + 동료평가 5%. SOLO Taxonomy 기반 평가 |
| AI 리터러시 사전-사후 변화 | 10% | 학기 초/말 AI 리터러시 설문(Long & Magerko, 2020 / AILQ 32문항) 사전-사후 비교 |

**평가 원칙**: 과정 중심 평가 — 코딩 과제의 Git 커밋 이력, 주석, 디버깅 과정을 평가에 포함. AI 탐지보다 교육적 접근을 우선한다.

---

## 8. AI 사용 정책

### AI 도구 허용 범위
- **적극 활용 권장**: 코딩 디버깅, API 문서 검색, 코드 예제 탐색에 AI 도구(GitHub Copilot, ChatGPT 등)를 사용할 수 있다. 단, Ma et al.(2025)의 안내된 사용 원칙에 따라 교수자가 제공하는 구조화된 가이드라인을 따른다.
- **제한**: 과제 코드 전체를 AI가 생성하는 것은 금지. 핵심 로직은 학생이 직접 작성하고, AI 보조는 디버깅/참조 수준으로 제한한다. AI 도구 사용 시 활용 내역을 과제 말미에 기술한다.
- **금지**: AI 윤리 분석 에세이에서 AI 생성 텍스트의 직접 제출 금지.

### 학술 무결성 기준
- 본 과목은 Stanford AIMES(2024) 프레임워크에서 **AI-Assigned** (코딩 실습) + **AI-Limited** (에세이/보고서) 수준을 혼합 적용한다.
- Perkins et al.(2024/2025) AIAS v2의 5단계 프레임워크에 따라 과목 내 AI 활용 수준을 명시한다.
- 코딩 과제의 학술 무결성은 과정 중심 평가(Git 커밋 이력 검토)로 확보한다.

### AI 결과물 인용 방법
- AI 코딩 보조 도구 사용 시: "GitHub Copilot(Microsoft, 2026)을 디버깅 참조에 활용하였음" 등으로 방법론 섹션에 기술한다.
- AI 생성 코드를 참조한 경우 해당 부분에 주석으로 표기한다.

---

## 9. 수업 규정

### 출석 정책
- 총 수업 시수의 75% 이상 출석 필수 (서울대학교 학칙 준수).
- 3회 이상 무단 결석 시 F 학점 부여.
- 코딩 실습 수업은 실시간 참여가 학습 효과에 핵심적이므로, 가능한 한 대면 출석을 권장한다.

### 과제 제출 정책
- 모든 과제는 Jupyter Notebook 형태로 LMS를 통해 마감일 23:59까지 제출한다.
- 코딩 과제: 코드 실행 가능 상태(reproducible)로 제출. 실행 불가 시 감점.
- 지각 제출: 1일당 10% 감점, 최대 3일까지 허용.
- 학술적 부정행위(코드 표절, 무단 AI 전체 생성 등) 적발 시 해당 과제 0점 처리.

---

## 10. 장애 학생 지원 안내

서울대학교 장애학생지원센터(02-880-8787)와 연계하여 다음 지원을 제공한다:
- 시험 시간 연장 (1.5배)
- 코딩 실습 시 보조 인력 배치
- 화면 확대/음성 지원 소프트웨어 제공
- 대체 과제 형태 협의
- 좌석 배치 및 접근성 조정

장애 학생은 학기 초 2주 이내에 담당 교수에게 개별 면담을 요청하여 필요한 지원을 협의할 수 있다.

---

*강의계획서 작성: 2026-03-25 | Inno-Edu 2031 Step 7*
*근거 소스: N2_evidence.md, curriculum_master_plan.md, 06_synthesis.md*
