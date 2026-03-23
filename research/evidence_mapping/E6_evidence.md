# E6 근거 매핑: 사회심리학 및 실험

> **과목 코드**: E6 | **모듈**: Behavior | **학년/학기**: 2학년 2학기
> **매핑 일자**: 2026-03-13
> **매핑 수행**: Claude Opus 4.6 Evidence Mapping Agent

---

## 1. 과목 개요

| 항목 | 현재 (As-Is) | 개편 후 (To-Be) |
|------|-------------|----------------|
| **핵심 내용** | 전통 실험 중심 | 소셜미디어 데이터 분석, 감성분석 추가 |
| **추가 내용** | — | SNS 데이터 수집, 텍스트 분석, 감성분석 실습 |
| **교수법** | 강의 60% + 실험 40% | 강의 40% + 데이터 실습 30% + PBL 30% |

### 개편 방향 요약

본 과목은 전통적 사회심리학 실험 패러다임을 유지하면서, 소셜미디어 빅데이터 분석과 자연어처리(NLP) 기반 감성분석을 추가하여 디지털 시대 사회심리학 연구역량을 배양한다. 재현성 위기(replication crisis) 교육과 오픈사이언스 실천을 통합하여 과학적 엄밀성을 강화한다.

---

## 2. Knowledge Tree 연계

| 분기 코드 | 분기명 | 연계 내용 | 연계 강도 |
|-----------|--------|----------|----------|
| **B1.4.1** | 사회·임상 실증 교육 | 사회심리학 교육 혁신의 핵심 근거 — 현명한 개입, 서비스러닝, 데이터 기반 교육 | **강** (Primary) |
| **B2.1.1** | LLM/GenAI 활용 | 소셜미디어 텍스트 분석에 LLM 활용, 감성분석 실습 | **강** (Primary) |
| **B2.2.2** | ML 응용 심리학 | 사회심리학 컴퓨터 모델링, NLP 기반 텍스트 데이터 분석 | **중** |
| **B2.2.4** | 오픈사이언스·재현성 | 재현성 위기 교육, 사전등록, 재현 연구 실습 | **중** |
| **B3.1** | PBL in STEM/Social Science | PBL 비중 30% 확대 근거 | **중** |
| **B3.2** | Active Learning | 능동학습 형평성 효과, TBL 적용 | **중** |

---

## 3. 핵심 교육 주제-근거 연계

> 본 매핑은 교육 주제별 근거 연계이며, 실제 주차별 구성은 담당 교수진이 강의계획서에서 결정한다. 강화 개편 과목의 경우, 기존 과목 구조를 유지하면서 아래 주제들을 통합하는 방식을 권장한다.

### 3.1 소셜미디어 데이터 수집 방법론

| 근거 소스 | 핵심 내용 | 근거 강도 |
|----------|----------|----------|
| Cushman (2024). Computational Social Psychology | ML/NLP의 사회심리학 연구 확산 입증, 사회인지 영역의 컴퓨터 모델링 적용 사례 | 강 |
| Bainbridge (2024). Big Data in Psychological Sciences | 컴퓨터 훈련 없는 학부생 대상 빅데이터 교재 | 중 |
| Nature Reviews Psychology (2024) | NLP의 행동과학 텍스트 데이터 분석 종합 리뷰 | 강 |
| NLP 서지분석 (P1-B2-014) | 1991-2023 심리학 NLP 4,909편 — 2012년 이후 기하급수적 성장 | 강 |

### 3.2 NLP/감성분석 실습 도입

| 근거 소스 | 핵심 내용 | 근거 강도 |
|----------|----------|----------|
| Ma et al. (2025). GenAI 메타분석 | 안내된 사용이 비안내 사용 대비 0.83 더 큰 효과, 구조화된 scaffolding 필수; 학습 성과 g=0.68 | 강 |
| Cushman (2024). 사회심리학 컴퓨터 모델링 | 감성분석의 사회심리학 연구 적용 사례, 사회심리학의 컴퓨터 모델링 응용 | 강 |
| LLM 심리학적 텍스트 분류 (P3-S010) | 최소 프로그래밍으로 LLM 기반 텍스트 분류 구현 가능 | 중 |
| Ben-Gurion University (2024) | 심리학 NLP 특화 데이터 사이언스 교과 — 벤치마크 모델 | 중 |
| Glasgow PsyTeachR (2024) | R 기반 재현 가능 연구 교육 — R 코딩 기반 텍스트 분석 실습 모델 | 중 |

### 3.3 컴퓨터 사회심리학 (Cushman 2024)

| 근거 소스 | 핵심 내용 | 근거 강도 |
|----------|----------|----------|
| Cushman (2024). *Annual Review of Psychology*, 75 | 사회인지 영역의 컴퓨터 모델링 적용, ML/NLP 연구 급속 확산, 컴퓨터 모델링은 전통 실험을 대체가 아닌 보완 | 강 |
| Abdurahman et al. (2024) | LLM의 WEIRD bias(142% 증가된 동의 확률) — AI 시대 문화적 편향 교육 자료 | 강 |
| Easterbrook (2025) | 사회심리학 원리의 교육 현장 적용 — "현명한 개입(wise interventions)"이 성취 격차 62% 감소, 4년 이상 효과 지속 | 중 |

### 3.4 재현성 위기와 사회심리학 (Nosek et al. 2015)

| 근거 소스 | 핵심 내용 | 근거 강도 |
|----------|----------|----------|
| Nosek et al. (2015). *Science*, 349(6251) | 100개 재현 연구 중 36%만 통계적 유의성 달성, 사회심리학 분야 재현율 특히 낮음(25%) | 강 |
| Korbmacher et al. (2023) | 재현성 위기를 '신뢰성 혁명'으로 재프레이밍 — 구조적·절차적·공동체 3차원 긍정적 변화 | 강 |
| Frank et al. (2025). *Experimentology*. MIT Press | 사전등록, 데이터 공유, 재현 가능 보고서의 통합 모델; 오픈사이언스 기반 실험 연구 워크플로 전체 재구성 | 강 |
| Markant & Galati (2023). OSCI | 오픈사이언스 개념 평가 도구(Open Science Concept Inventory) | 중 |
| Pownall et al. (2023) | 사전등록 집단이 오픈사이언스 이해도 유의미 향상 | 중 |
| Thibault et al. (2024) | 103명 전문가 델파이 — 9개 연구방법론 기술 권고 | 강 |
| Peirce et al. (2019/2022). PsychoPy2 | 온라인 실험 설계 교육 인프라 | 중 |

### 3.5 PBL 30% 도입

| 근거 소스 | 핵심 내용 | 근거 강도 |
|----------|----------|----------|
| Kozanitis & Nenciovici (2023) | 인문/사회과학 능동학습 메타분석 ES=0.489 — 심리학에서 효과 특히 높음 | 강 |
| Schneider et al. (2025) | PBL 2차 메타분석 — ES=0.60 (CI [0.49, 0.71]), PBL 기반 발표 평가 | 강 |
| Theobald et al. (2020) | 고강도 능동학습(67%+)만 성취 격차 축소에 유의미 | 강 |
| Zhang & Ma (2023) | PBL 메타분석 — 최적 그룹 크기 4-5명, 최적 기간 9-18주 | 강 |
| 박하은 외 (2023) | 국내 대학 PBL 메타분석 — 사회과학에서 PBL 효과 상위권 | 중 |
| Freeman et al. (2014) | Active learning 메타분석(225개 연구) — 0.47 SD 향상, PBL 설계 원리 적용 | 강 |
| Bringle & Reeb (2016) | 서비스러닝이 APA 학부 심리학 전공 목표 달성에 가장 강력한 교수법 | 중 |
| Fleckney et al. (2024) | 형성적 동료 피드백이 가장 효과적 — 평가자 훈련, 다중 리뷰 반복 | 중 |
| Breland et al. (2023) | UCLA LA 프로그램 — 메타인지 인식 +1.92점, 자기효능감 +0.56점 | 강 |

### 3.6 기존 과목 구조 유지 주제 (기초 이론·방법론·윤리·평가)

| 주제 영역 | 근거 소스 | 핵심 내용 | 근거 강도 |
|----------|----------|----------|----------|
| 과학적 방법론·교육 프레임워크 | APA (2023). Guidelines 3.0 | Goal 2 과학적 탐구, Cross-Cutting Theme: 문화적 다양성과 사회적 맥락; Goal 2: 연구 설계, 데이터 분석, 해석 역량 | 강 |
| 온라인 행동 데이터 윤리 | Chan (2023). AI 정책 3대 차원 | 교수법·거버넌스·운영 — 소셜미디어 연구의 윤리적 프레임워크 | 중 |
| 온라인 행동 데이터 윤리 | 교육부·대교협 (2024-2025) | AI 윤리 가이드라인 — 5대 핵심 원칙(학문적 진실성, 인간중심성, 투명성, 공정성, 정보보호) | 중 |
| 학습 성과 평가 | Biggs & Collis (1982/2014). SOLO Taxonomy | BMBM 4대 모듈 전체 적용 가능한 평가 프레임워크 | 강 |
| AI 활용 수준 평가 | Perkins et al. (2024/2025). AIAS v2 | AI 활용 수준 차등 설정의 글로벌 표준 도구 | 중 |

---

## 4. 교수법 종합 근거

### 4.1 PBL 30% 도입 근거

| 근거 항목 | 소스 | 핵심 수치/발견 |
|----------|------|--------------|
| PBL 전체 효과 | Schneider et al. (2025). 2차 메타분석 | ES=0.60 (CI [0.49, 0.71]) |
| 사회과학 PBL 효과 | 박하은 외 (2023). 국내 PBL 메타분석 | 사회과학 분야 상위권 효과 |
| PBL 형평성 | Theobald et al. (2020). PNAS | 성취 격차 시험 33%, 합격률 45% 축소 |
| 최적 그룹/기간 | Zhang & Ma (2023) | 4-5명, 9-18주 |
| 인문/사회과학 특화 | Kozanitis & Nenciovici (2023) | ES=0.489, 심리학에서 특히 높은 효과 |

### 4.2 데이터 실습 30% 도입 근거

| 근거 항목 | 소스 | 핵심 수치/발견 |
|----------|------|--------------|
| 컴퓨터 모델링 확산 | Cushman (2024). Annual Review of Psychology | 사회심리학 ML/NLP 연구 급속 확산 |
| NLP 성장 추세 | NLP 서지분석 (P1-B2-014) | 4,909편, 2012년 이후 기하급수적 성장 |
| GenAI 교육 효과 | Ma et al. (2025). JCAL 메타분석 | g=0.68, 안내된 사용 시 효과 극대화 |
| 비전공자 코딩 교수법 | learnr/Shiny OER (P1-B2-019) | 인터랙티브 환경에서 시작, 점진적 독립 코딩 |

### 4.3 능동학습 전략

| 전략 | 근거 소스 | 적용 방법 |
|------|----------|----------|
| 플립드 클래스룸 | 플립드 2차 메타분석: g=0.726 | 이론 강의를 사전 영상으로, 수업 시간은 토론/실습 |
| TBL(Team-Based Learning) | TBL 우산 리뷰(P1-B3-012): 312+ 연구 | iRAT/tRAT → 팀 응용 → 동료평가 |
| 서비스러닝 | Bringle & Reeb (2016) | 지역사회 기반 사회심리학 프로젝트 |
| 인출 연습 | Roberts (2016). 심리학 연구방법론 | 매주 퀴즈를 통한 핵심 개념 인출 연습 |

---

## 5. 평가 도구 근거

| 평가 영역 | 도구/방법 | 근거 소스 | 적용 방안 |
|----------|----------|----------|----------|
| 학습 성과 | SOLO Taxonomy | Biggs & Collis (1982/2014) | 다구조적-확장적 추상-관계적 수준으로 보고서 평가 |
| 오픈사이언스 이해도 | OSCI (Open Science Concept Inventory) | Markant & Galati (2023) | 사전-사후 측정으로 오픈사이언스 교육 효과 평가 |
| AI 활용 수준 | AIAS v2 (AI Assessment Scale) | Perkins et al. (2024/2025) | 5단계 중 Level 2-3(AI 보조 분석) 설정 |
| PBL 프로젝트 평가 | 형성적 동료평가 + 루브릭 | Fleckney et al. (2024); 한국 PBL 루브릭 (P3-S018) | 팀 기여도 자기/동료평가, 포트폴리오 |
| 비판적 사고 | CPS 기반 평가 | Xu et al. (2023). CPS 메타분석 ES=0.82 | 협력적 문제해결 과제를 통한 비판적 사고 측정 |
| 감성분석 역량 | 실습 산출물 평가 | Cushman (2024); NLP 리뷰 (P1-B2-013) | 코드 재현성, 분석 타당성, 해석 정확성 기준 |

---

## 6. 글로벌 벤치마크

| 기관 | 프로그램/접근 | 본 과목 시사점 | 소스 |
|------|-------------|--------------|------|
| **Stanford AIMES** | 4차원 AI 리터러시, 3대 교수 전략(AI-Assigned/Limited/Prohibited) | 감성분석 실습에서 AI 활용 수준 차등 설정 — 초반 AI-Prohibited(기초 개념), 후반 AI-Assigned(실습) | Stanford CTL (2024) |
| **Harvard Bok Center** | 주간 Lab Workshops, AI 사용 수준 스펙트럼 | 데이터 실습 주차에 Lab Workshop 형태 운영 | Derek Bok Center (2023) |
| **Glasgow PsyTeachR** | 학부-대학원 전 수준 R 기반 재현 가능 연구 교육 | R 기반 텍스트 분석/감성분석 실습 — Level 1-3 체계적 경로 참조 | Glasgow PsyTeachR (2024) |
| **Ben-Gurion University** | 심리학 NLP 특화 데이터 사이언스 교과 | 사회심리학 텍스트 데이터 분석 실습의 교과 설계 모델 | Ben-Gurion (2024) |
| **고려대 심리학부** | 5대 혁신 사회주제 중 "Mind & Machine" | 디지털 사회심리학 접근의 국내 선례 | 고려대 심리학부 (2021) |

---

## 7. 구현 권고사항

### 7.1 우선순위 과제

| 우선순위 | 과제 | 근거 | 일정 |
|---------|------|------|------|
| **P0** | 소셜미디어 데이터 수집·분석 실습 모듈 개발 | Cushman (2024); NLP 리뷰 (P1-B2-013) | 2026.03-06 |
| **P0** | 감성분석 실습 교재/튜토리얼 제작 | Ma et al. (2025); LLM 텍스트 분류 (P3-S010) | 2026.03-06 |
| **P1** | 사회심리학 재현 연구 PBL 시나리오 설계 | Nosek et al. (2015); Frank et al. (2025) | 2026.06-07 |
| **P1** | 동료평가 루브릭 개발 | Fleckney et al. (2024); 한국 PBL 루브릭 (P3-S018) | 2026.06-07 |
| **P2** | OSCI 사전-사후 평가 체계 구축 | Markant & Galati (2023) | 2026.09 |

### 7.2 인프라 요건

| 요건 | 세부 내용 | 근거 |
|------|----------|------|
| 소프트웨어 | R/RStudio (tidytext, sentimentr 패키지), Python (NLTK, Hugging Face) | Glasgow PsyTeachR (2024); Dalmaijer et al. (2024) |
| 데이터 접근 | Twitter/X Academic API 또는 대안 SNS 데이터셋 | Cushman (2024) |
| AI 도구 | ChatGPT/Claude API 접근(감성분석 보조) | Ma et al. (2025) — 안내된 사용 scaffolding 필수 |
| 실험 도구 | PsychoPy/Pavlovia (재현 연구용) | Peirce et al. (2019/2022) |

### 7.3 위험 요인 및 대응

| 위험 | 대응 전략 | 근거 |
|------|----------|------|
| 학생 코딩 역량 부족 | N3(심리데이터 분석I) 선이수 권장, learnr/Shiny 기반 인터랙티브 실습 시작 | 비전공자 코딩 교수법 (P1-B2-019) |
| 소셜미디어 데이터 접근 제한 | 사전 수집된 공개 데이터셋 확보, 시뮬레이션 데이터 병행 | Bainbridge (2024) |
| AI 윤리 이슈 | 매 실습에 윤리적 사용 가이드라인 내재화, WEIRD bias 교육 | Abdurahman et al. (2024); Chan (2023) |
| 전통 실험 비중 축소 우려 | 전통 실험과 디지털 방법의 균형 유지, 양 접근의 상호 보완성 강조 | Cushman (2024) — 컴퓨터 모델링은 전통 실험을 대체가 아닌 보완 |

### 7.4 APA Guidelines 3.0 정렬

| APA Goal | 본 과목 연계 내용 |
|----------|-----------------|
| Goal 1: 지식 기반 | 사회심리학 핵심 이론(태도, 귀인, 사회적 영향, 집단역학) |
| Goal 2: 과학적 탐구 | 실험 설계, 사전등록, 감성분석, 데이터 기반 연구 |
| Goal 3: 윤리적·사회적 책임 | 소셜미디어 연구 윤리, AI 편향(WEIRD bias), 데이터 프라이버시 |
| Goal 4: 소통 | PBL 프로젝트 발표, 동료평가, 연구 보고서 작성 |
| Goal 5: 전문성 개발 | 디지털 연구 역량, AI 활용 능력, 오픈사이언스 실천 |

---

## 참고문헌 (근거 소스 요약)

### Primary Sources (직접 인용)

1. Cushman, F. (2024). Computational social psychology. *Annual Review of Psychology*, 75, 625-652.
2. Open Science Collaboration [Nosek et al.] (2015). Estimating the reproducibility of psychological science. *Science*, 349(6251), aac4716.
3. Freeman, S. et al. (2014). Active learning increases student performance. *PNAS*, 111(23), 8410-8415.
4. Ma, S. et al. (2025). A meta-analysis of the impact of GenAI on learning outcomes. *JCAL*.
5. Theobald, E.J. et al. (2020). Active learning narrows achievement gaps. *PNAS*, 117(12), 6476-6483.
6. APA (2023). Guidelines for the Undergraduate Psychology Major, Version 3.0.
7. Korbmacher, M. et al. (2023). The replication crisis has led to positive changes. *Communications Psychology*, 1(1), Article 3.
8. Markant, D.B. & Galati, A. (2023). Development of OSCI. *Collabra: Psychology*, 9(1).
9. Frank, M.C. et al. (2025). Experimentology. MIT Press.
10. Kozanitis, A. & Nenciovici, L. (2023). Active learning in humanities/social sciences meta-analysis. *Higher Education*, 86, 1377-1394.
11. 박하은 외 (2023). 국내 대학 PBL 메타분석. *학습자중심교과교육연구*, 23(6).
12. Easterbrook, M.J. (2025). Using social psychology to create inclusive education. *BJSP*.
13. Bringle, R.G. & Reeb, R.N. (2016). *Service Learning in Psychology*. APA.

### Secondary Sources (간접 참조)

14. Schneider, M. et al. (2025). PBL second-order meta-analysis. *Educational Research Review*.
15. Zhang, L. & Ma, Y. (2023). PjBL meta-analysis. *Frontiers in Psychology*, 14.
16. Peirce, J. et al. (2019/2022). PsychoPy2. *Behavior Research Methods*, 51.
17. Biggs, J.B. & Collis, K.F. (1982/2014). SOLO Taxonomy. Academic Press.
18. Perkins, M. et al. (2024/2025). AIAS v2. *JUTLP*.
19. Glasgow PsyTeachR Team (2024). Reproducible Research in R. https://psyteachr.github.io/
20. Chan, C.K.Y. (2023). AI policy education framework. *IJETHE*, 20, Article 38.

---

*E6 Evidence Mapping 완료 | 고유 근거 소스: 20편 | 2026-03-13*
