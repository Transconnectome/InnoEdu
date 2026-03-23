# E7 근거 매핑: 조직심리학

> **과목 코드**: E7 | **모듈**: Behavior | **학년/학기**: 3학년 2학기
> **매핑 일자**: 2026-03-13
> **매핑 수행**: Claude Opus 4.6 Evidence Mapping Agent

---

## 1. 과목 개요

| 항목 | 현재 (As-Is) | 개편 후 (To-Be) |
|------|-------------|----------------|
| **핵심 내용** | 이론 중심 | HR analytics, 빅데이터 성격분석 추가 |
| **추가 내용** | — | HR 데이터 분석, 조직 네트워크 분석, 빅데이터 활용 |
| **교수법** | 강의 70% + 사례 30% | 강의 40% + 데이터 실습 30% + PBL 30% |

### 개편 방향 요약

본 과목은 전통적 조직심리학(I-O Psychology) 이론 기반 위에 피플 애널리틱스(People Analytics)와 빅데이터 기반 조직행동 분석 역량을 추가한다. HR 데이터 분석, 조직 네트워크 분석(ONA), 빅데이터 성격 측정 등 데이터 사이언스 기법을 통합하여, I-O 심리학과 데이터 과학의 교차 영역에서 연구·실무 역량을 배양한다.

---

## 2. Knowledge Tree 연계

| 분기 코드 | 분기명 | 연계 내용 | 연계 강도 |
|-----------|--------|----------|----------|
| **B1.4.3** | 조직·경제 빅데이터 응용 | I-O 심리학과 피플 애널리틱스 융합, 빅데이터 트렌드 | **강** (Primary) |
| **B2.2.2** | ML 응용 심리학 | ML/NLP의 조직행동 연구 적용 — 성격 예측, 직무 분석 | **강** (Primary) |
| **B2.2.3** | 빅데이터 방법론 | HR 빅데이터 수집·분석·해석 방법론 | **강** (Primary) |
| **B2.2.1** | 데이터분석 교육과정 설계 | R/Python 기반 HR 데이터 분석 교육 모델 | **중** |
| **B3.1** | PBL in STEM/Social Science | PBL 비중 30% 확대, 사례기반학습(CBL) 적용 | **중** |
| **B3.2** | Active Learning | 능동학습, TBL, 사례 분석 기반 교수법 | **중** |

---

## 3. 핵심 교육 주제-근거 연계

> 본 매핑은 교육 주제별 근거 연계이며, 실제 주차별 구성은 담당 교수진이 강의계획서에서 결정한다. 강화 개편 과목의 경우, 기존 과목 구조를 유지하면서 아래 주제들을 통합하는 방식을 권장한다.

### 3.1 People Analytics / HR 데이터 분석 도입

| 근거 소스 | 핵심 내용 | 근거 강도 |
|----------|----------|----------|
| Saboe et al. (2025). SIOP White Paper | I-O 심리학과 피플 애널리틱스가 행동과학/데이터과학 핵심에서 중첩; I-O 심리학자의 역할 정의; I-O + 데이터과학 통합 실무 역량 | 중 |
| Huselid (2023). The Rise of People Analytics | 피플 애널리틱스의 HR 분야 확산 동향; HR 데이터의 4단계 성숙 모델(기술적→진단적→예측적→처방적) | 중 |
| Oswald et al. (2020). *Annual Review of OPB*, 7 | I-O 심리학의 빅데이터 활용 체계적 리뷰; 빅데이터 방법론(텍스트 마이닝, 소셜 미디어 분석, 센서 데이터); 빅데이터가 SIOP 2019-2020 상위 3대 트렌드 | 강 |
| IIT (2024-2025). People Analytics M.S. | I-O 심리학 15학점 + 통계/데이터사이언스 15학점 통합 모델 | 중 |
| Glasgow PsyTeachR (2024) | R 기반 재현 가능 연구 — R 코딩 기반 데이터 분석 실습 모델 | 중 |
| Neth (2024). ds4psy | R 패키지 기반 심리학 데이터 사이언스 교재 | 중 |

### 3.2 조직 네트워크 분석 (ONA)

| 근거 소스 | 핵심 내용 | 근거 강도 |
|----------|----------|----------|
| Oswald et al. (2020) | 소셜 네트워크 분석의 I-O 심리학 적용 — 커뮤니케이션 패턴, 영향력 매핑 | 강 |
| Bainbridge (2024). Big Data in Psychological Sciences | 네트워크 분석 학부 교육 모델 | 중 |
| Ma et al. (2025). GenAI 메타분석 | 안내된 AI 활용으로 복잡한 네트워크 시각화 보조; 학습 성과 g=0.68 | 강 |

### 3.3 빅데이터 성격 평가

| 근거 소스 | 핵심 내용 | 근거 강도 |
|----------|----------|----------|
| Oswald et al. (2020) | 소셜 미디어/디지털 흔적 기반 성격 평가 연구 리뷰 | 강 |
| Cushman (2024). Computational Social Psychology | 개인차 연구의 컴퓨터 모델링 접근; ML 기반 행동 예측 모델의 조직 적용; ML의 심리학 연구 확산 — 지도학습 기반 성과 예측 모델 | 강 |
| NLP 서지분석 (P1-B2-014) | 심리학 NLP 4,909편 — 성격/정서 예측 관련 연구 급증 | 강 |
| ML 응용 심리학 (P1-B2-010) | ML의 행동과학 적용 체계적 리뷰 — 예측 모델링 교육 | 중 |
| Nature Reviews Psychology (2024) | NLP의 행동과학 텍스트 데이터 분석 종합 리뷰 | 강 |
| LLM 텍스트 분류 (P3-S010) | 최소 프로그래밍으로 LLM 기반 텍스트 분류 — 직원 설문/리뷰 분석 | 중 |
| Ben-Gurion University (2024) | 심리학 NLP 특화 데이터 사이언스 교과 | 중 |

### 3.4 I-O 심리학 데이터 사이언스 (Oswald et al. 2020)

| 근거 소스 | 핵심 내용 | 근거 강도 |
|----------|----------|----------|
| Oswald et al. (2020). *Annual Review of OPB*, 7 | 빅데이터 분석 워크플로; I-O 심리학의 빅데이터 활용 체계적 리뷰 | 강 |
| Ma et al. (2025). GenAI 메타분석 | 안내된 AI 사용으로 ML 실습 보조; g=0.68 | 강 |
| 데이터 시각화 + AI (P1-B2-027) | AI가 수동 탐지 불가능 패턴 발견 — 127편 리뷰 | 중 |

### 3.5 PBL 30% 도입

| 근거 소스 | 핵심 내용 | 근거 강도 |
|----------|----------|----------|
| Kozanitis & Nenciovici (2023) | 인문/사회과학 능동학습 메타분석 ES=0.489 | 강 |
| Schneider et al. (2025) | PBL 2차 메타분석 — ES=0.60 (CI [0.49, 0.71]) | 강 |
| Theobald et al. (2020) | 고강도 능동학습(67%+)만 성취 격차 축소에 유의미 | 강 |
| Zhang & Ma (2023) | PBL 메타분석 — 최적 그룹 크기 4-5명, 발표 기반 평가 | 강 |
| 박하은 외 (2023) | 국내 대학 PBL 메타분석 — 사회과학 상위권 | 중 |
| Freeman et al. (2014) | Active learning 메타분석 — TBL/사례 분석 기반 교수법 적용 근거 | 강 |
| Bringle & Reeb (2016) | 서비스러닝 — 조직 컨설팅 프로젝트 기반 학습 모델 | 중 |
| Fleckney et al. (2024) | 형성적 동료 피드백이 가장 효과적 | 중 |
| Breland et al. (2023) | UCLA LA 프로그램 — 메타인지 +1.92점, 자기효능감 +0.56점 | 강 |
| UPenn Wharton (2024-2025) | 행동경제학 전공의 심리학-경제학 학제간 교과 구조 — PBL 발표 모델 | 중 |

### 3.6 기존 과목 구조 유지 주제 (기초 이론·윤리·평가)

| 주제 영역 | 근거 소스 | 핵심 내용 | 근거 강도 |
|----------|----------|----------|----------|
| I-O 심리학 교육 프레임워크 | APA (2023). Guidelines 3.0 | Goal 5 전문성 개발, I-O 심리학 직업 경로; Cross-Cutting Theme: 다양성, 형평성, 포용성(DEI) | 강 |
| 조직 내 동기·개입 설계 | Easterbrook (2025) | 사회심리학의 "현명한 개입" — 조직 내 동기·리더십 개입 설계 연구 | 중 |
| AI 윤리·알고리즘 공정성 | Chan (2023). AI 정책 3대 차원 | 조직 내 AI 활용의 윤리적 프레임워크 | 중 |
| AI 윤리·알고리즘 공정성 | Baker & Hawn (2022) | 알고리즘 편향 — 인종·성별·SES 등 채용/평가 알고리즘 편향 분류 | 중 |
| AI 윤리·알고리즘 공정성 | 교육부·대교협 (2024-2025) | AI 윤리 가이드라인 — 5대 핵심 원칙 | 중 |
| 학습 성과 평가 | Biggs & Collis (1982/2014). SOLO Taxonomy | 평가 프레임워크 | 강 |
| AI 활용 수준 평가 | Perkins et al. (2024/2025). AIAS v2 | AI 활용 수준 차등 설정 | 중 |

---

## 4. 교수법 종합 근거

### 4.1 PBL 30% 도입 근거

| 근거 항목 | 소스 | 핵심 수치/발견 |
|----------|------|--------------|
| PBL 전체 효과 | Schneider et al. (2025). 2차 메타분석 | ES=0.60 (CI [0.49, 0.71]) |
| 사회과학 PBL 효과 | 박하은 외 (2023). 국내 PBL 메타분석 | 사회과학 분야 상위권 효과 |
| PBL 형평성 | Theobald et al. (2020). PNAS | 성취 격차 시험 33%, 합격률 45% 축소 |
| CBL 적합성 | Zhang et al. (2023). 15개 RCT, 2,172명 | CBL이 PBL보다 구조화되어 학부 심리학에 적합 |
| 인문/사회과학 특화 | Kozanitis & Nenciovici (2023) | ES=0.489, 심리학에서 특히 높은 효과 |

### 4.2 데이터 실습 30% 도입 근거

| 근거 항목 | 소스 | 핵심 수치/발견 |
|----------|------|--------------|
| I-O + 피플 애널리틱스 융합 | Saboe et al. (2025). SIOP White Paper | 행동과학/데이터과학 핵심 중첩 영역 |
| 빅데이터 I-O 트렌드 | Oswald et al. (2020). Annual Review | SIOP 상위 3대 트렌드 |
| HR 데이터 분석 교육 모델 | IIT (2024-2025). People Analytics M.S. | I-O 15학점 + DS 15학점 통합 모델 |
| GenAI 실습 보조 | Ma et al. (2025). JCAL 메타분석 | g=0.68, 안내된 사용 시 효과 극대화 |
| 심리학 DS 교재 | Neth (2024). ds4psy | R 기반 심리학 데이터 사이언스 |

### 4.3 능동학습 전략

| 전략 | 근거 소스 | 적용 방법 |
|------|----------|----------|
| CBL(Case-Based Learning) | Zhang et al. (2023). CBL 메타분석 | 실제 조직 사례를 기반으로 분석·진단·솔루션 도출 |
| TBL(Team-Based Learning) | TBL 우산 리뷰 (P1-B3-012) | 조직 진단 팀 프로젝트 — iRAT/tRAT → 팀 분석 → 발표 |
| 플립드 클래스룸 | 플립드 2차 메타분석: g=0.726 | 이론 강의를 사전 영상으로, 수업 시간은 데이터 분석 실습 |
| 서비스러닝 | Bringle & Reeb (2016) | 실제 조직/비영리 대상 컨설팅 프로젝트 |

---

## 5. 평가 도구 근거

| 평가 영역 | 도구/방법 | 근거 소스 | 적용 방안 |
|----------|----------|----------|----------|
| 학습 성과 | SOLO Taxonomy | Biggs & Collis (1982/2014) | 다구조적-확장적 추상-관계적 수준으로 보고서 평가 |
| AI 활용 수준 | AIAS v2 (AI Assessment Scale) | Perkins et al. (2024/2025) | Level 3-4(AI 보조 분석-AI 협업) 설정 |
| PBL 프로젝트 평가 | 형성적 동료평가 + 루브릭 | Fleckney et al. (2024); 한국 PBL 루브릭 (P3-S018) | 팀 기여도 자기/동료평가, HR 분석 포트폴리오 |
| HR 분석 역량 | 실습 산출물 평가 | Saboe et al. (2025); Oswald et al. (2020) | 코드 재현성, 분석 타당성, 비즈니스 인사이트 도출 |
| 비판적 사고 | CPS 기반 평가 | Xu et al. (2023). CPS 메타분석 ES=0.82 | 조직 문제 진단 과제를 통한 비판적 사고 측정 |
| 윤리적 추론 | 알고리즘 공정성 사례 분석 | Baker & Hawn (2022); Chan (2023) | AI 채용 도구의 편향 분석 및 윤리적 의사결정 보고서 |

---

## 6. 글로벌 벤치마크

| 기관 | 프로그램/접근 | 본 과목 시사점 | 소스 |
|------|-------------|--------------|------|
| **IIT (Illinois Institute of Technology)** | People Analytics M.S. — I-O 15학점 + DS 15학점 | 학부 수준 축소판으로 I-O + 데이터 분석 통합 교과 설계 | IIT (2024-2025) |
| **UPenn Wharton** | 행동경제학 BS — 심리학-경제학 학제간 교과 구조 | 조직행동-경제학-데이터 분석의 학제간 접근 참조 | UPenn Wharton (2024-2025) |
| **Stanford AIMES** | 4차원 AI 리터러시, 3대 교수 전략 | HR 데이터 분석에서 AI 활용 수준 차등 설정 | Stanford CTL (2024) |
| **Glasgow PsyTeachR** | 전 수준 R 기반 재현 가능 연구 교육 전환 | R 기반 HR 데이터 분석 실습 모델 | Glasgow PsyTeachR (2024) |
| **고려대 심리학부** | 5대 혁신 사회주제 중 "Workplace Well-being" | I-O 심리학 + 데이터 기반 교육 혁신의 국내 선례 | 고려대 심리학부 (2021) |
| **SIOP** | People Analytics 백서 (2025) | I-O 심리학자의 피플 애널리틱스 역할·역량 정의 | Saboe et al. (2025) |

---

## 7. 구현 권고사항

### 7.1 우선순위 과제

| 우선순위 | 과제 | 근거 | 일정 |
|---------|------|------|------|
| **P0** | HR 데이터 분석 실습 모듈 개발 (이직 예측, 성과 분석) | Saboe et al. (2025); Oswald et al. (2020) | 2026.03-06 |
| **P0** | 조직 네트워크 분석(ONA) 실습 튜토리얼 제작 | Oswald et al. (2020); Bainbridge (2024) | 2026.03-06 |
| **P1** | 빅데이터 성격 측정 PBL 시나리오 설계 | Oswald et al. (2020); Cushman (2024) | 2026.06-07 |
| **P1** | CBL 사례 개발 (실제 조직 HR 데이터 기반) | Zhang et al. (2023). CBL 메타분석 | 2026.06-07 |
| **P2** | 알고리즘 공정성 평가 루브릭 개발 | Baker & Hawn (2022); Chan (2023) | 2026.09 |

### 7.2 인프라 요건

| 요건 | 세부 내용 | 근거 |
|------|----------|------|
| 소프트웨어 | R/RStudio (tidyverse, igraph, caret 패키지), Python (scikit-learn, networkx) | Glasgow PsyTeachR (2024); Neth (2024) |
| 데이터셋 | HR Analytics 공개 데이터셋 (IBM HR Analytics, Kaggle People Analytics) | Oswald et al. (2020) |
| AI 도구 | ChatGPT/Claude API (분석 보조, 텍스트 마이닝) | Ma et al. (2025) — 안내된 사용 scaffolding 필수 |
| 벤치마크 교재 | Bainbridge (2024). Big Data in Psychological Sciences | 컴퓨터 훈련 없는 학부생 대상 설계 |

### 7.3 위험 요인 및 대응

| 위험 | 대응 전략 | 근거 |
|------|----------|------|
| 학생 데이터 분석 역량 부족 | N3(심리데이터 분석I) 선이수 권장; E1(심리통계학) 필수 선수과목 유지 | 비전공자 코딩 교수법 (P1-B2-019) |
| 실제 HR 데이터 접근 제한 | 공개 데이터셋(IBM, Kaggle) + 시뮬레이션 데이터 활용; 산학 협력 파트너십 구축 | Bainbridge (2024); Oswald et al. (2020) |
| AI 윤리 이슈 (채용 알고리즘 편향) | 매 실습에 공정성 점검 가이드라인 내재화; 알고리즘 편향 사례 필수 교육 | Baker & Hawn (2022); Chan (2023) |
| 이론-실습 균형 유지 | 이론 → 피플 애널리틱스 기초 → 빅데이터 응용 → 통합 프로젝트 순의 단계적 설계 | Saboe et al. (2025) — I-O 이론이 데이터 분석의 기반 |
| 3학년 수준 ML 이해 난이도 | ML 기초 개념(지도학습, 교차검증)만 소개, 코드 실행 보조에 AI 튜터 활용 | Ma et al. (2014). ITS 메타분석 g=0.42-0.86 |

### 7.4 APA Guidelines 3.0 정렬

| APA Goal | 본 과목 연계 내용 |
|----------|-----------------|
| Goal 1: 지식 기반 | 조직심리학 핵심 이론(동기, 리더십, 직무 만족, 조직문화, 인사 선발) |
| Goal 2: 과학적 탐구 | HR 데이터 분석, ML 기반 예측 모델, 조직 네트워크 분석 |
| Goal 3: 윤리적·사회적 책임 | 알고리즘 공정성, AI 채용 편향, 직원 데이터 프라이버시 |
| Goal 4: 소통 | PBL 조직 진단 보고서 작성, 비즈니스 프레젠테이션, 동료평가 |
| Goal 5: 전문성 개발 | I-O 심리학 진로 탐색, 피플 애널리틱스 실무 역량, 데이터 기반 의사결정 |

### 7.5 Behavior-Method 모듈 교차 설계

| 교차 영역 | Method 모듈 연계 | Behavior 모듈 기여 |
|----------|-----------------|------------------|
| R/Python 코딩 | N3(심리데이터 분석I)에서 기초 습득 | E7에서 HR 데이터에 적용 |
| ML 기초 | N2(AI for Psych)에서 개념 학습 | E7에서 이직 예측, 성과 예측에 적용 |
| 데이터 시각화 | N3에서 ggplot2/matplotlib 습득 | E7에서 ONA 시각화, HR 대시보드에 적용 |
| 연구윤리 | N1(연구 입문)에서 기초 교육 | E7에서 AI 채용 윤리, 직원 데이터 보호에 적용 |

---

## 참고문헌 (근거 소스 요약)

### Primary Sources (직접 인용)

1. Saboe, K. et al. (2025). Maximizing Impact: I-O Psychology and People Analytics. *SIOP White Paper*.
2. Oswald, F.L. et al. (2020). Big data in I-O psychology and HRM. *Annual Review of OPB*, 7, 505-533.
3. Cushman, F. (2024). Computational social psychology. *Annual Review of Psychology*, 75, 625-652.
4. Huselid, M.A. (2023). The rise of people analytics. *Research in Personnel and HRM*, 41, 1-18.
5. Freeman, S. et al. (2014). Active learning increases student performance. *PNAS*, 111(23), 8410-8415.
6. Ma, S. et al. (2025). A meta-analysis of the impact of GenAI on learning outcomes. *JCAL*.
7. APA (2023). Guidelines for the Undergraduate Psychology Major, Version 3.0.
8. IIT (2024-2025). M.S. in People Analytics Curriculum.
9. UPenn Wharton (2024-2025). Behavioral Economics BS.
10. Baker, R.S. & Hawn, A. (2022). Algorithmic bias in education. *IJAIED*.
11. Kozanitis, A. & Nenciovici, L. (2023). Active learning in humanities/social sciences meta-analysis. *Higher Education*, 86, 1377-1394.
12. 박하은 외 (2023). 국내 대학 PBL 메타분석. *학습자중심교과교육연구*, 23(6).

### Secondary Sources (간접 참조)

13. Schneider, M. et al. (2025). PBL second-order meta-analysis. *Educational Research Review*.
14. Zhang, L. & Ma, Y. (2023). PjBL meta-analysis. *Frontiers in Psychology*, 14.
15. Zhang, Y. et al. (2023). CBL meta-analysis. *BMC Medical Education*, 23, 609.
16. Theobald, E.J. et al. (2020). Active learning narrows achievement gaps. *PNAS*, 117(12).
17. Neth, H. (2024). ds4psy. https://bookdown.org/hneth/ds4psy/
18. Bainbridge, W.A. (2024). Big Data in the Psychological Sciences. Cambridge UP.
19. Biggs, J.B. & Collis, K.F. (1982/2014). SOLO Taxonomy. Academic Press.
20. Perkins, M. et al. (2024/2025). AIAS v2. *JUTLP*.
21. Glasgow PsyTeachR Team (2024). Reproducible Research in R. https://psyteachr.github.io/
22. Chan, C.K.Y. (2023). AI policy education framework. *IJETHE*, 20, Article 38.
23. Easterbrook, M.J. (2025). Using social psychology to create inclusive education. *BJSP*.
24. Bringle, R.G. & Reeb, R.N. (2016). *Service Learning in Psychology*. APA.

---

*E7 Evidence Mapping 완료 | 고유 근거 소스: 24편 | 2026-03-13*
