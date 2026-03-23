# InnoEdu 2031 Scoping Review: AI 시대 심리학 학부교육 혁신을 위한 근거 종합

> **프로젝트**: Inno-Edu 2031 서울대학교 심리학과 창의교육프로젝트
> **보고 표준**: PRISMA-ScR (Tricco et al., 2018)
> **방법론 프레임워크**: Arksey & O'Malley (2005) + JBI Manual (Peters et al., 2020)
> **작성일**: 2026-03-13

---

## 초록

**배경**: 생성형 AI의 급속한 확산은 심리학 학부교육의 교과과정, 교수법, 연구 훈련 전반에 근본적 전환을 요구하고 있다. 서울대학교 심리학과는 Inno-Edu 2031 사업을 통해 기존 39개 전공 과목을 Brain-Mind-Behavior-Method(BMBM) 4대 모듈로 재편하고, 14개 과목을 신설 또는 강화 개편하며, PBL 비중을 13%에서 50%로 확대하는 교육 혁신을 추진하고 있다.

**목적**: 본 범위 검토(scoping review)는 이 교육 혁신의 근거 기반을 구축하기 위해 다음 세 가지 연구 질문을 설정하였다. (1) BMBM 모듈형 교과과정의 설계 원리와 선행 사례는 무엇인가? (2) AI·데이터 사이언스를 심리학 교육에 통합하는 방법론과 효과는 무엇인가? (3) PBL 및 능동적 학습, 학부생 연구역량, 교수 역량, 글로벌 벤치마크, 평가·거버넌스에 관한 최선의 근거는 무엇인가?

**방법**: Arksey & O'Malley(2005) 5단계 프레임워크에 따라, PsycINFO, ERIC, Web of Science, Scopus, PubMed, IEEE Xplore, arXiv 등 7개 학술 데이터베이스와 Google Scholar, KCI/RISS, 기관 웹사이트를 포함한 grey literature를 대상으로 4단계 반복적 검색(P0 예비연구 60편, P1 핵심문헌 205편, P2 확장문헌 165편, P3 갭필·심화 170편)을 수행하였다. PCC(Population-Concept-Context) 프레임워크에 기반한 포함/제외 기준을 적용하였으며, MMAT과 AACODS를 활용한 품질 평가를 실시하였다.

**결과**: 최종 600편이 포함되었으며, 7개 분기(B1-B7), 29개 하위분기, 97개 리프 카테고리에 걸쳐 100% 커버리지를 달성하였다. Tier 1(peer-reviewed) 비율은 72.2%(433편)로 목표(≥50%)를 초과하였고, 2020년 이후 출판물이 약 87%, 한국어 소스가 54편(9.0%)을 차지하였다. PBL의 학습 성과 효과(ES = 0.44-0.64), 능동학습의 성취 격차 축소(33-45%), 생성형 AI의 안내된 사용 효과(g = 0.68), 오픈사이언스의 제도적 확산, 모듈형 교과과정 설계 원리, 학부생 연구 프로그램 모범 사례 등에 관한 강력한 근거가 확인되었다.

**결론**: 본 리뷰는 서울대 심리학과 BMBM 교과과정 개편이 국제적 표준(APA Guidelines 3.0, BPS 인증)에 부합하며, 풍부한 실증 근거에 의해 뒷받침됨을 확인하였다. 14개 과목별 근거 매핑과 APA 학습목표 정렬 매트릭스를 통해 교과과정 개편의 구체적 실행 방향을 제시한다.

---

## 1. 서론

### 1.1 배경: AI 시대 심리학 교육의 도전

2022년 이후 대규모 언어 모델(LLM)과 생성형 AI의 급속한 확산은 고등교육 전반에 전례 없는 변화를 요구하고 있다. 심리학은 이 변화의 핵심 교차점에 위치한다. 한편으로 AI 기술은 심리학의 연구 방법론, 데이터 수집·분석, 임상 실무를 근본적으로 변혁하고 있으며(Cushman, 2024; Stade et al., 2024), 다른 한편으로 심리학은 AI 시대에 인간 인지, 행동, 정서를 과학적으로 탐구하는 학문으로서 그 교육적 가치가 재조명되고 있다.

이러한 맥락에서 심리학 학부교육은 세 가지 핵심 도전에 직면해 있다. 첫째, 전통적인 분과 중심 교과과정은 AI·데이터 사이언스·신경과학의 학제간 융합이라는 현실을 반영하지 못하고 있다. 둘째, 강의 중심 교수법은 능동적 학습, 문제기반학습(PBL), 연구 기반 교육의 효과에 관한 축적된 근거와 괴리되어 있다. 셋째, 학부생의 연구 역량 훈련은 AI 도구의 연구 파이프라인 통합, 오픈사이언스 실천, 재현성 혁명(credibility revolution)이라는 새로운 패러다임에 대응해야 한다.

APA Guidelines 3.0(2023)은 이러한 변화를 반영하여 5대 교육 목표를 개정하고, EDI(형평성·다양성·포용성), 기술 통합, 응용, 글로벌/사회문화적 관점의 4대 Cross-Cutting Integrative Themes를 도입하였다. BPS/QAA(2023-2024) 역시 7개 핵심 교과 영역과 EDI 교차주제를 새로이 제시하였다. 이러한 국제적 표준의 수렴은 심리학 교육의 체계적 혁신이 개별 기관의 선택이 아닌 글로벌 트렌드임을 시사한다.

서울대학교 심리학과는 이러한 도전에 대응하여 Inno-Edu 2031 창의교육프로젝트를 통해 기존 39개 전공 과목을 Brain-Mind-Behavior-Method(BMBM) 4대 모듈로 재편하는 교육 혁신을 추진하고 있다. 본 사업은 1차년도(2026.3.1-2026.12.31) 예산 70,000,000원 규모로, 14개 과목 신설/개편(41%), PBL 비중 확대(13%→50%), AI·데이터 기반 연구역량 체계 구축, 학부생 연구 파이프라인 강화를 핵심 축으로 설정하였다.

### 1.2 근거: BMBM 프레임워크의 필요성

BMBM 프레임워크는 심리학 전공 39개 과목을 4대 모듈 -- Brain(뇌, 11개 과목, 28%), Mind(마음, 8개 과목, 20.5%), Behavior(행동, 12개 과목, 31%), Method(방법, 8개 과목, 20.5%) -- 로 재편하는 구조적 혁신이다. 이 프레임워크의 필요성은 다음의 근거에 기초한다.

첫째, 심리학은 본질적으로 뇌-마음-행동의 통합적 이해를 지향하는 학문이다. 그러나 전통적인 분과 중심 교과과정에서는 인지신경과학, 인지심리학, 사회·임상심리학, 연구방법론이 독립적으로 운영되어 학생들이 이들 간의 유기적 연결을 파악하기 어려웠다. BMBM 모듈 구조는 이러한 분절을 극복하고, 학생이 뇌의 생물학적 기제(Brain), 인지적 과정(Mind), 행동적 발현(Behavior), 그리고 이를 탐구하는 방법론(Method)을 연결된 체계로 이해하도록 설계되었다.

둘째, AI 시대에 심리학은 "인간 이해의 중심" 학문으로서 새로운 역할을 요구받고 있다. AI 의식에 대한 과학적 평가 프레임워크(Butlin et al., 2023), 인지과학-AI 양방향 통합 이론(Lake & Gureckis, 2024), LLM의 심리학 전 분야 응용(P3-S009)은 심리학과 AI의 교차점이 교육의 핵심 주제임을 보여준다. Method 모듈에 4개 신설 과목(심리학 연구 입문, 심리과학을 위한 인공지능, 심리데이터 분석 I, 학부생 연구 캡스톤)을 배치한 것은 이러한 시대적 요구에 대한 직접적 대응이다.

셋째, 글로벌 선도 대학들이 유사한 방향의 교육 혁신을 추진하고 있다. Harvard MBB(Mind Brain Behavior) 프로그램, NYU Computational Cognitive Modeling, Stanford AIMES, MIT DAILy 등은 학제간 통합과 AI·데이터 역량 강화를 핵심 전략으로 채택하고 있다. 본 사업은 이러한 글로벌 선도 모델을 참조하되, 심리학 고유의 BMBM 통합 강점을 살린 차별화된 접근을 지향한다.

### 1.3 목적: 연구 질문

본 범위 검토의 상위 연구 질문(Overarching RQ)은 다음과 같다:

> AI 시대에 심리학 학부 교육을 Brain-Mind-Behavior-Method 프레임워크로 혁신하기 위해 어떤 근거, 모델, 도구, 정책이 존재하는가?

이 상위 질문은 7개의 하위 연구 질문(Sub-RQs)으로 구체화된다:

1. **RQ1 (B1)**: BMBM 모듈형 교과과정의 설계 원리와 선행 사례는 무엇인가?
2. **RQ2 (B2)**: AI·데이터 사이언스를 심리학 교육에 통합하는 방법론과 효과는 무엇인가?
3. **RQ3 (B3)**: PBL 및 능동적 학습(active learning)의 심리학 교육 효과에 대한 근거는 무엇인가?
4. **RQ4 (B4)**: 학부생 연구역량 파이프라인의 모범 사례와 효과는 무엇인가?
5. **RQ5 (B5)**: 교수 AI 역량 개발의 효과적 모델과 사례는 무엇인가?
6. **RQ6 (B6)**: 글로벌 선도 대학의 심리학 교육 혁신 전략과 정책은 무엇인가?
7. **RQ7 (B7)**: 교육 성과 측정, 프로그램 평가, 거버넌스의 검증된 도구와 프레임워크는 무엇인가?

---

## 2. 방법

### 2.1 프로토콜 및 등록

본 범위 검토는 Arksey & O'Malley(2005)의 5단계 프레임워크를 1차 방법론으로 채택하고, PRISMA-ScR(Tricco et al., 2018) 22개 항목 체크리스트에 따라 보고하며, JBI Manual(Peters et al., 2020)의 PCC 프레임워크로 포함 기준을 구조화하였다. 상세 프로토콜 문서(`research_protocol_600.md`)가 연구 수행 전에 작성되었으나, PROSPERO 등 공식 등록소에 사전 등록하지는 않았다. 이는 교육학 범위 검토에서 프로토콜 등록이 권장 사항이나 필수는 아닌 점(JBI Manual), 그리고 교육학 분야에서 프로토콜 미등록이 아직 일반적인 점을 고려한 것이다.

본 연구는 AI 보조 반복적 검색(AI-assisted iterative search) 방법론을 채택하였다. Claude AI(Anthropic)를 활용하여 7개 분기(B1-B7)에 각 1명의 AI 에이전트를 배정하고, 4단계 반복 검색-선별-차팅 주기를 수행하였다. 이 방법론의 투명성 확보를 위해 별도의 AI 보조 방법론 투명성 선언을 PRISMA-ScR 흐름도 문서에 포함하였다.

### 2.2 적격 기준 (PCC)

JBI Manual(Peters et al., 2020) 권고에 따라, PCC(Population-Concept-Context) 프레임워크로 포함/제외 기준을 구조화하였다.

| PCC 요소 | 포함 기준 | 제외 기준 |
|----------|----------|----------|
| **Population (대상)** | 심리학, 행동과학, 신경과학 학부 교육 프로그램, 교수자, 학생 | K-12 교육, 비교육 임상 연구, 대학원 전용 프로그램 |
| **Concept (개념)** | 교과과정 설계, AI/데이터 통합, PBL/능동적 학습, 학부생 연구, 교수 개발, 평가·거버넌스 | 순수 기술 개발, 비교육 AI 연구, 비심리학 교과 |
| **Context (맥락)** | 고등교육 기관(글로벌), 2015-2026 출판(AI 관련: 2020-2026), 영어/한국어 | 2010년 이전(기초 이론 예외), 비공인 출판물, 영어/한국어 외 언어 |

**기초 이론 예외 규정**: 2010년 이전 출판물이라도 해당 분야의 기초적·개념적 프레임워크로 널리 인용되는 경우 포함하였다(예: SOLO Taxonomy 1982, FLC 2004, TPACK 2006).

### 2.3 정보원

다음 10개 데이터베이스 및 추가 소스를 검색하였다.

**학술 데이터베이스(7개)**:
- PsycINFO (심리학 전문) -- B1, B2, B3, B4, B7
- ERIC (교육학) -- B1, B3, B4, B5
- Web of Science (다학제) -- B1, B2, B6
- Scopus (다학제) -- B2, B3
- PubMed/PMC (의생명·신경과학) -- B1, B2
- IEEE Xplore (공학/AI) -- B2
- arXiv (프리프린트) -- B2

**한국어 데이터베이스(2개)**: KCI, RISS

**Grey literature**: 기관 웹사이트(Stanford CTL, Harvard Bok Center, MIT), APA/APS 출판물, CUR 출판물, UNESCO/OECD 보고서, Google Scholar

### 2.4 검색 전략 (4단계 P0-P3)

검색은 4단계 반복적 프로세스로 수행되었다. 각 단계에서 이전 단계의 결과가 후속 단계의 검색 전략에 반영되는 반복적 정제(iterative refinement) 방식을 채택하였다.

**P0 예비연구(Pilot, 60편)**: 7개 분기별 초기 키워드 검색을 통해 Knowledge Tree 구조를 검증하고 검색 전략을 교정하였다. 7명의 AI 에이전트가 분기당 1명씩 병렬로 검색을 수행하였다.

**P1 핵심문헌(Core, 205편)**: P0 결과를 기반으로 키워드를 정제하고, 데이터베이스별 체계적 검색을 수행하여 29개 하위분기의 핵심 근거 기반을 구축하였다.

**P2 확장문헌(Extended, 165편)**: 리프 카테고리 중심 검색과 KCI/RISS 한국어 검색을 수행하여 97개 리프 100% 커버리지를 달성하고 한국어 소스 36편을 확보하였다.

**P3 갭필·심화(Gap-fill, 170편)**: 5대 전략을 병행하였다: (1) 리프 갭필 71편(41.8%) -- 5편 미만 리프 집중 보강, (2) Forward citation chaining 39편(22.9%) -- 핵심 시드 논문 피인용 추적, (3) Backward citation chaining 20편(11.8%) -- 리뷰/메타분석 참고문헌 역추적, (4) 2025-2026 최신 출판물 24편(14.1%), (5) Grey literature/한국어 16편(9.4%).

7개 분기별 검색 키워드는 각 분기의 핵심 주제에 맞게 영문 및 한국어로 설계되었으며, 불리언 검색식(Boolean operators)을 사용하였다. 전체 검색 키워드 세트는 별도 문서(`search_prompts.md`)에 기록되었다.

### 2.5 소스 선정 (Tier 시스템)

소스 선정은 AI 보조 PCC 기반 제목/초록 선별, 전문(full-text) 검토, Tier 분류, 품질 평가의 순서로 이루어졌다. 3단계 Tier 분류 체계를 적용하였다.

| Tier | 근거 수준 | 소스 유형 | 품질 평가 도구 | 목표 비율 |
|------|----------|----------|-------------|----------|
| **Tier 1** | peer-reviewed | 학술 저널, 체계적 리뷰, 메타분석 | MMAT (Hong et al., 2018) | ≥50% |
| **Tier 2** | 기관 검증 | 기관 보고서, 정부 출판물, APA/APS 문서, 학회 proceedings | AACODS (Tyndall, 2010) | ≤30% |
| **Tier 3** | 실무 가치 | 프로그램 웹사이트, 교육과정 자료, 기관 사례 기술 | AACODS + "맥락 참조" 태그 | ≤20% |

서지 검증은 CrossRef API를 통한 DOI 검증(292건, 95.9% 성공)과 WebSearch를 통한 제목/저자 교차 검증(non-DOI 소스 118/125건 검증)으로 수행되었으며, 최종 실질적 오류율은 0.3%(2/600)로 확인되었다.

### 2.6 데이터 차팅

Arksey & O'Malley(2005) Stage 4에 따라, 포함된 600편 전체에 대해 표준 데이터 추출 양식 8개 항목을 적용하였다: (1) 서지정보(저자, 연도, 제목, 출처, DOI/URL), (2) Knowledge Tree 위치(분기, 하위분기, 리프), (3) 소스 유형 및 Tier, (4) PCC 적합성, (5) 핵심 발견(3-5개), (6) 서울대 적용 시사점, (7) 관련 소스 교차참조, (8) 품질 평가(MMAT 또는 AACODS). 차팅 결과는 Phase별·분기별 28개 파일로 관리되었다.

---

## 3. 결과

### 3.1 선정 과정 (PRISMA 흐름도 참조)

본 범위 검토의 소스 선정 과정은 4단계 반복 검색(P0→P1→P2→P3)을 통해 수행되었다. 전통적 PRISMA 흐름도가 가정하는 단일 패스 파이프라인과 달리, 각 Phase는 독립적인 식별→선별→적격성→포함 주기를 포함하며, 이전 단계의 결과가 후속 단계의 검색 전략에 반영되었다.

**식별(Identification)**: 7개 학술 데이터베이스, 2개 한국어 데이터베이스, grey literature, citation chaining을 통해 누적 약 3,900-6,600건의 레코드가 식별되었다(추정). 중복 제거 후 약 2,500-4,000건이 선별 대상이 되었다. AI 보조 검색의 특성상 데이터베이스별 정확한 히트 수는 개별 기록이 불가하여 범위로 제시한다.

**선별(Screening)**: AI 보조 PCC 기반 제목/초록 선별을 통해 약 1,300-2,200건이 제외되었다. 주요 제외 사유는 비교육 초점(순수 임상/기술 연구), 비고등교육(K-12, 비공식), 언어 제한(영어/한국어 외), 시기 제한(2015 이전, 기초 이론 예외 제외)이었다. 선별 통과 건수는 약 1,200-1,800건으로 추정된다.

**적격성(Eligibility)**: 전문(full-text) 검토를 통해 PCC 상세 기준 불충족, 전문 접근 불가, 중복/유사 내용, 품질 기준 미달 등의 사유로 약 450-950건이 제외되었다. 기초 이론 예외 규정(2010년 이전 기초적 프레임워크)이 적용되었다.

**포함(Inclusion)**: 최종 600편이 데이터 차팅을 완료하고 포함되었다. P0(60편) + P1(205편) + P2(165편) + P3(170편) = 600편. 최종 품질 감사 결과 실질적 오류율 0.3%(2/600)로 PASS 판정을 받았다.

상세 PRISMA-ScR 흐름도는 별도 문서(`prisma_flow_diagram.md`)에 전체 누적 흐름과 단계별 반복 흐름의 이중 구조로 제시되어 있다.

### 3.2 소스 특성 (연도/Tier/언어/분기 분포)

포함된 600편의 주요 특성은 다음과 같다.

**분기별 분포**:

| 분기 | 편수 | 비율 | P0 | P1 | P2 | P3 |
|------|------|------|-----|-----|-----|-----|
| B1 BMBM 교과과정 설계 | 110 | 18.3% | 12 | 40 | 30 | 29 |
| B2 AI·데이터 방법론 | 100 | 16.7% | 10 | 30 | 25 | 35 |
| B3 PBL 수업혁신 | 90 | 15.0% | 9 | 30 | 25 | 26 |
| B4 학부생 연구역량 | 80 | 13.3% | 8 | 25 | 20 | 27 |
| B5 교수역량 강화 | 70 | 11.7% | 7 | 25 | 20 | 18 |
| B6 글로벌 벤치마크 | 80 | 13.3% | 9 | 25 | 25 | 21 |
| B7 측정·평가·거버넌스 | 70 | 11.7% | 7 | 30 | 20 | 14 |
| **합계** | **600** | **100%** | **60** | **205** | **165** | **170** |

7개 분기 전체가 목표 편수를 100% 달성하였으며, 29개 하위분기(≥5편)와 97개 리프 카테고리(≥1편) 모두 100% 커버리지를 확보하였다.

**Tier 분포**:

| Tier | 편수 | 비율 | 설명 |
|------|------|------|------|
| Tier 1 (peer-reviewed) | 433 | 72.2% | 목표(≥50%) 초과 달성 |
| Tier 2 (기관 검증) | ~133 | ~22.2% | 기관 보고서, APA/APS 문서 등 |
| Tier 3 (실무 가치) | ~34 | ~5.7% | 프로그램 웹사이트, 교육과정 자료 등 |

B6(글로벌 벤치마크) 분기의 Tier 1 비율(28.8%)이 타 분기 대비 낮은 것은 해당 분기가 프로그램 소개, 정책 문서, 기관 보고서를 핵심 소스 유형으로 포함하는 구조적 특성에 기인하며, P0-P3 전 단계에서 일관된 패턴으로 확인되었다.

**연도 분포**:

| 기간 | 비율 |
|------|------|
| 2023-2026 | ~74-90% |
| 2020-2022 | ~8-15% |
| 2015-2019 | ~2-5% |
| ≤2014 (기초이론 예외) | ~1-3% |

2020년 이후 출판물이 약 87%를 차지하여 목표(≥60%)를 크게 초과하였다. 이는 AI 시대 교육 혁신이라는 주제 특성상 최신 문헌의 비중이 높은 것을 반영한다.

**언어 분포**: 영어 약 546편(91.0%), 한국어 54편(9.0%). 한국어 소스는 P2에서 36편, P3에서 18편이 추가되어 목표 범위(50-55편) 내에서 달성되었다. 한국어 소스는 한국 고등교육 정책, 국내 대학 PBL 메타분석, AI 윤리교육 현황, 종단 패널 조사 등 한국 맥락의 고유한 근거를 제공한다.

### 3.3 분기별 핵심 발견

#### 3.3.1 B1 교과과정 설계

B1 분기는 110편(Tier 1 비율 66.4%, 2020년 이후 85.5%)을 종합하여 BMBM 모듈형 교과과정 설계의 근거 기반을 구축하였다. 5개 하위분기(B1.1 교과과정 개편 이론, B1.2 Brain 모듈, B1.3 Mind 모듈, B1.4 Behavior 모듈, B1.5 Method 모듈)에 걸쳐 핵심 발견을 도출하였다.

**모듈형 설계의 효과와 조건**: 모듈형 교과과정은 학생 중심 교수-학습 과정을 강화하고 교수자 역할을 학습 촉진자로 전환하나(Getahun et al., 2019), 인지심리학 원리(분산학습, 인출연습, 통합 전략)가 반드시 수반되어야 모듈 간 분절적 학습을 방지할 수 있다(Hartley, 2020). 공학교육 분야 33편 체계적 리뷰(Mesutoglu et al., 2024)는 모듈 간 독립성과 통합성의 균형, 순차적/병렬적 배치, 학습 목표 정렬이 핵심 설계 원리임을 확인하였다. 또한 교과 설계(course design)가 교수자 역량보다 학생의 교육 품질 평가와 참여를 더 강력하게 예측하는 것으로 나타났다(Aman et al., 2024). 이 발견은 BMBM 4대 모듈이 각 모듈 내 수직적 심화(Intro→Intermediate→Advanced)와 모듈 간 수평적 교차 이수 요건을 동시에 설계해야 함을 시사한다.

**역량기반교육(CBE)의 글로벌 확산**: CBE는 미국 128개 기관 851개 학부 프로그램에서 운영 중이며(Nodine, 2016), 159편 체계적 리뷰(Tahirsylaj & Sundberg, 2025)는 CBE가 5가지 비전과 3가지 과정을 통해 초국가적으로 확산·변형되어 왔음을 입증하였다. ADDIE 모델을 통한 역순 설계(backward design)가 역량 숙달 검증에 효과적이며(Linder, 2023), OECD의 지식·기술·태도·가치 통합 프레임워크가 이론적 기반을 제공한다(Johnstone & Soares, 2022). BMBM 교과과정은 각 모듈별 역량 정의→평가 설계→학습 활동 배치의 역순 설계 원리를 채택하고, APA 3.0의 학습 성과 지표를 역량 기준으로 활용하는 것이 적절하다.

**국제 표준 수렴과 Brain/Mind/Behavior/Method 모듈 근거**: APA Guidelines 3.0(2023)의 5대 교육 목표와 Cross-Cutting Themes, BPS/QAA(2023-2024)의 7개 핵심 교과 영역은 심리학 교육의 국제적 표준이 수렴하고 있음을 보여준다. Brain 모듈에서는 119명 교육자 대상 설문(Chen et al., 2023)과 103명 SfN 작업 세션(Phillips et al., 2023)을 통해 8대 핵심 개념이 도출되었으며, 저비용 EEG 장비를 활용한 학부 실습의 실현 가능성이 확인되었다(Ratti et al., 2019). Mind 모듈에서는 인지과학의 5대 학습전략의 교실 적용(Coley & Tanner, 2019), 온라인 심리물리학 실습의 타당성(Zhao et al., 2022; Marin-Campos et al., 2025), AI 의식 탐구의 철학적 기반(Butlin et al., 2023)이 핵심 발견으로 도출되었다. Behavior 모듈에서는 사회심리학의 "현명한 개입"이 성취 격차를 62% 감소시킨다는 근거(Easterbrook, 2025), 종단 데이터(ABCD Study, 한국 패널) 활용 교육의 체계화(Saragosa-Harris et al., 2022), I-O 심리학과 피플 애널리틱스의 융합(Saboe et al., 2025)이 확인되었다. Method 모듈에서는 JASP/jamovi의 SPSS 대체 가능성(Field et al., 2025; Shepherd & Richardson, 2024), 오픈사이언스 통합 실험법(Frank et al., 2025; Thibault et al., 2024), R/Python 기반 통계 교육의 글로벌 전환 추세(Glasgow PsyTeachR; Navarro, 2022)가 강력한 근거로 확인되었다.

#### 3.3.2 B2 AI·데이터 교육

B2 분기는 100편(Tier 1 비율 77.0%, 근거 강도 분포: 강 29편, 중 48편, 약 23편)을 종합하여 AI·데이터 사이언스의 심리학 교육 통합에 관한 근거를 구축하였다.

**생성형 AI의 교육 효과와 안내된 사용의 중요성**: 4편의 메타분석과 2편의 RCT를 포함한 강력한 근거가 확인되었다. Ma et al.(2025)의 메타분석에서 GenAI의 전체 학습 성과 효과 크기는 g = 0.68(p < 0.001)이었으며, 안내된 사용(instructed use)이 비안내 사용 대비 효과 크기가 0.83 더 큰 것으로 나타났다. ChatGPT 학부생 메타분석에서도 Hedges' g = 1.14(SE = 0.185)의 큰 긍정적 효과가 확인되었다. 29개 실험/준실험 분석에서 안내된 사용 조건에서 유의미하게 더 큰 고차 사고력 향상 효과가 확인되어, GenAI 활용 시 구조화된 프롬프트 가이드라인과 교수 설계(scaffolding)가 필수적임이 입증되었다.

**AI 튜터링 시스템의 효과**: Ma et al.(2014)의 ITS 메타분석(107 효과크기, 14,321명)에서 AI 튜터링은 교사 주도 수업 대비 g = 0.42, 비ITS 컴퓨터 대비 g = 0.57의 효과를 보였다. Harvard RCT(Kestin et al., 2025, N = 194)에서는 AI 튜터가 교실 내 능동적 학습 대비 유의미하게 높은 성과를 달성하였다. 30개 연구 메타분석에서 ITS 전체 효과크기는 g = 0.86으로 확인되어, BMBM 모듈 전반에 AI 튜터 도입의 근거가 확보되었다.

**데이터 사이언스 교과과정의 글로벌 확산과 오픈사이언스 제도화**: 심리학 특화 데이터 사이언스 교과과정이 글로벌 확산 추세에 있으며, R/tidyverse 기반이 표준으로 자리잡고 있다. Konstanz 대학 ds4psy(Neth, 2024), Wake Forest DataScience4Psych(Garrison, 2024-2025), Penn LPS 데이터 분석-심리학 통합 학위 등이 대표 사례이다. ML/NLP 기법은 심리학 연구 전 분야에서 급속히 확산되고 있으며(Cushman, 2024; Nature Reviews Psychology NLP 리뷰), 4,909편 서지분석은 2012년 이후 기하급수적 성장을 입증하였다. 오픈사이언스의 '신뢰성 혁명'은 Nosek et al.(2015)의 100개 재현 연구(36%만 유의), Korbmacher et al.(2023)의 구조적·절차적·공동체 3차원 긍정적 변화 프레이밍을 통해 제도화되고 있다.

**AI 보조 연구 파이프라인**: AI 기반 문헌검색 자동화는 스크리닝 부담을 60% 이상 감소시키면서 90% 이상 재현율을 유지하는 것으로 확인되었다. ESM/디지털 표현형은 심리학 데이터 수집 패러다임을 변혁하고 있으며, AI 보조 논문작성은 구조화·편집 단계에서 효과적이나 비판적 분석·독창성에는 한계가 있어 허용 범위의 명확한 규정이 필요하다.

#### 3.3.3 B3 PBL·교수법

B3 분기는 90편(Tier 1 비율 91.1%, 메타분석 22편 포함)을 종합하여 PBL 비중 13%→50% 확대의 학술적 근거를 구축하였다. 이 분기는 본 리뷰 전체에서 가장 높은 Tier 1 비율과 가장 많은 메타분석을 포함하여, 근거 강도가 특히 강력하다.

**PBL의 학습 성과 효과 -- 강력한 메타분석 근거**: Freeman et al.(2014, PNAS, 7,600+ 인용)의 225개 연구 메타분석에서 능동학습 조건의 시험 성적은 0.47 SD 향상되었으며, 전통 강의 학생의 낙제 확률은 1.5배(낙제율 55% 증가)였다. Zhang & Ma(2023)의 66개 연구 PjBL 메타분석에서 전체 효과크기는 SMD = 0.441(p < 0.001)이었으며, 최적 그룹 크기 4-5명, 최적 기간 9-18주가 확인되었다. Schneider et al.(2025)의 20개 1차 메타분석을 종합한 2차 메타분석에서 PBL 전체 효과크기는 ES = 0.60(CI [0.49, 0.71])이었다. 50개 연구(5,210명) 메타분석에서 PBL의 비판적 사고 효과는 SMD = 0.640(p < 0.001)으로, 상급생, 6명 이상 그룹, 장기 개입에서 더 강한 효과가 나타났다.

**능동학습의 형평성(equity) 효과**: Theobald et al.(2020, PNAS)의 메타분석에서 능동학습은 소외계층 학생의 성취 격차를 시험 점수에서 33%, 합격률에서 45% 축소하였다. 다만, 고강도 능동학습(수업시간의 67-100%)만이 성취 격차 축소에 유의미한 효과를 보여, PBL 비중 50% 이상 -- 형평성 관점에서는 67% 이상 -- 의 목표 설정이 정당화된다. Kozanitis & Nenciovici(2023)의 104개 연구 인문/사회과학 메타분석에서 효과크기는 ES = 0.489 SD이었으며, 심리학을 포함한 사회과학에서 효과가 특히 높은 것으로 나타났다.

**플립드 클래스룸과 TBL의 효과**: 플립드 클래스룸의 2차 메타분석에서 학습 성과 효과크기는 g = 0.726(p < .0001)이었으며, 심리학 학부생 통계 모듈에서의 직접 적용(Playfoot, 2023)이 성공적으로 보고되었다. TBL에 대한 우산 리뷰(2013-2024년 23개 리뷰, 312+ 1차 연구, 63,987+ 참가자)는 인지적 수행의 일관된 향상을 확인하였으며, 자기결정이론(SDT)의 자율성, 유능감, 관계성 충족이 심리학적 기제로 규명되었다. 한국 대학 맥락에서 116편 국내 PBL 메타분석(박하은 외, 2023)은 사회과학에서의 PBL 효과가 상위권(인문 > 사회과학 > 예체능 > 자연과학 > 공학)임을 확인하였으며, 온라인 PBL 40편 메타분석(이동건 & 이희숙, 2024)에서 전체 효과크기는 0.704(중간 수준)로 나타났다.

**AI 강화 교수법과 Learning Assistant 제도**: 적응형 학습 시스템의 69개 연구 스코핑 리뷰(du Plooy & Casteleijn, 2024)에서 학업 성과 향상 59%, 학생 참여 증가 36%가 보고되었다. GenAI의 학습 성과 효과크기는 SMD = 0.45이었으나, 하위 인지(이해, 적용)에서만 유의미하고 상위 인지(창작, 평가)에는 효과가 미미하여 교수자 안내의 중요성이 재확인되었다. UCLA LA 프로그램(443명)에서 메타인지 인식(MAI) +1.92점, 자기효능감 +0.56점의 효과가 확인되었으며, LA 모델 도입 기관의 대학 수료율이 4-15 퍼센트포인트 더 높은 것으로 나타나 양방향 교육 효과가 입증되었다.

#### 3.3.4 B4 학부생 연구역량

B4 분기는 80편(P0 8편, P1 25편, P2 20편, P3 27편)을 종합하여 학부생 연구역량 파이프라인의 근거를 구축하였다. 12개 핵심 발견 중 강 7개(58.3%), 중 5개(41.7%)로 약 등급 발견이 없다.

**학부 연구 참여(URP)의 고영향 교육 효과**: Krim et al.(2024)의 6개 대학 120,308명 대규모 실증 연구에서 URP 참여 학생은 비참여 유사집단 대비 4년 졸업 가능성 2배, 6년 졸업 가능성 10배 이상이며, 유색인종·저소득층·1세대 학생의 형평성 격차가 6년 시점에서 완전 해소되는 것으로 확인되었다. Lopatto(2010)의 SURE 설문(1,135명+)은 전문적·개인적·인지적 이점을 다기관에서 확인하였고, Ahmad & Al-Thani(2022)의 PRISMA 기반 체계적 리뷰(114편)는 URP 모델 유형화의 근거를 제공한다. 이 발견은 10주 연구지도 프로그램과 N4(캡스톤)의 HIP(High-Impact Practice) 프레임워크 채택을 정당화한다.

**멘토링 구조화와 CURE 설계**: Shanahan et al.(2015)의 10가지 효과적 멘토링 실천, Limeri et al.(2024)의 MURS 도구(지지적-파괴적 멘토링 7개 하위 요인), BUILD EXITO/BUMMP의 다중 멘토 모델(교수-대학원생-동료)이 대규모 프로그램 운영의 근거로 확인되었다. 캡스톤 수준 CURE에서는 Auchincloss et al.(2014)의 5차원(과학적 실천, 발견, 관련성, 협력, 반복) 설계 원리가 확립되었으며, Shanle et al.(2024)의 170명 종단 연구는 높은 좌절감이 도전-관심 관계를 부정적으로 조절하나, 높은 의미 부여가 관심 유지와 연관됨을 확인하였다. 허미선 & 이정민(2021)의 국내 캡스톤 메타분석(21편, 83건 효과크기)은 전체 효과크기 0.96(큰 효과)을 보고하여, 졸업논문 3트랙 시스템의 국내 맥락 근거를 제공한다.

**연구윤리·IRB·학술출판**: Katsarov et al.(2022)의 메타분석은 사례 기반 학습, 소그룹 토론, 성찰적 글쓰기가 가장 효과적이며 교과과정 내 통합이 단기 워크숍보다 장기 효과가 우수함을 확인하였다. Harvard CUHS(2024) 모델의 90분 대면 대화형 IRB 훈련, FAIR 원칙 기반 RDM 교육, APA 7판 학습에서 능동적 작성 연습(production)의 우월성(Boysen, 2019; Neubauer & Hernaiz-Sanchez, 2025)이 핵심 근거로 도출되었다. 미국 상위 60개 대학 교수 이력서 분석에서 83.4%가 학부생과 최소 1편을 공저 출판한 것으로 나타나(Giuliano et al., 2023), 학술 출판 지원 체계의 필요성이 뒷받침된다.

#### 3.3.5 B5 교수 역량 개발

B5 분기는 70편(P0 7편, P1 25편, P2 20편, P3 18편; Tier 1 74.3%)을 종합하여 교수 AI 역량 개발의 근거를 구축하였다. 12개 핵심 발견 중 강 5개, 중 7개이다.

**TPACK-AI 확장과 교수 AI 리터러시 프로파일**: Mishra & Koehler(2006)의 TPACK 프레임워크가 I-TPACK/AI-TPACK으로 확장·실증되었다. 6개월 개입 연구(실험군 64명)에서 I-TPACK 기반 교수 개발 프로그램이 AI Technological Knowledge와 AI Technological Pedagogical Knowledge 영역에서 유의미한 효과를 보였다. Stockdale et al.(2024)의 잠재 클래스 분석(122명)에서 AI 사용에 대한 4가지 프로파일(낙관적, 비판적, 비판적 성찰, 중립)이 도출되어, 획일적 훈련의 한계와 맞춤형 교수 개발의 필요성이 확인되었다. 이 발견은 AI Teaching Bootcamp를 BMBM 모듈별 내용(Content)-교수법(Pedagogy)-AI 기술(Technology)의 통합적 역량 개발로 설계하고, 교수 프로파일별 차별화된 트랙(초보자/실천가/비판적 활용자)을 편성해야 함을 시사한다.

**FLC와 교수법 변화의 지속성**: Cox(2004)의 FLC 모델(12명 이하, 학제간, 자발적 참여)이 20년간 후속 연구에서 지속적으로 검증되었다. Tomkin et al.(2019)은 FLC 참여 교수의 교수법 변화가 종료 후 2년까지 지속됨을 종단 추적으로 실증하였고, Liu et al.(2024)의 16,072명 SEM 분석은 PLC가 디지털 전문성-디지털 수업 통합 간 매개 효과를 대규모로 확인하였다. Teaching Innovation Pods(TIP) 12명 교수진 구성이 FLC 이론에 부합하며, AI Bootcamp(단기)→TIP 월간 모임(지속)→온라인 자원(비동기)의 3층 교수 개발 구조가 근거에 기반한다.

**장벽과 기관 거버넌스**: Brownell & Tanner(2012)의 4대 장벽(훈련·시간·인센티브·정체성)이 AI 시대에도 유효하며, 유럽 8개 대학 68명 연구는 감정적 압도감과 직업 안정성 공포를 추가 식별하였다. Stanford HAI-AIMES 모델의 다층적 거버넌스, 가천대 60명 60시간 부트캠프(1인당 500만원 강의개발비), 대교협 약 50개 AI 교수법 과정 등 한국 생태계의 급속한 형성이 확인되었다. SoTL(Scholarship of Teaching and Learning)의 Teaching Commons 비전(Huber & Hutchings, 2005)이 TIP의 장기 발전 방향으로 제안된다.

#### 3.3.6 B6 글로벌 벤치마크

B6 분기는 80편(P0 9편, P1 25편, P2 25편, P3 21편)을 종합하여 15개 핵심 발견을 도출하였다. 강 7개, 중 8개이다.

**"실험 + 가드레일" AI 거버넌스 합의**: Stanford AISAC의 7대 원칙, Harvard Bok Center의 AI 사용 수준 스펙트럼, NUS의 "Use AI + X+AI" 2축 프레임워크가 대표적이다. 5개국 343개 대학 비교 연구에서 문화적·규제적 차이에도 불구하고 "교수자 재량 기반 자율적 통합"이 지배적 경향으로 확인되었다. Stanford HAI 2026 AI+Education Summit에서 제기된 "평가 위기(Assessment Crisis)" — 학생 프로젝트가 학습 과정의 지표가 되지 못하는 문제 — 는 학습 결과물에서 학습 과정 평가로의 전환 필요성을 부각한다.

**APA 3.0 정렬과 국제 인증 수렴**: APA Guidelines 3.0의 5대 교육 목표는 BMBM 4대 모듈에 체계적으로 매핑되며(Goal 1→Brain/Mind/Behavior, Goal 2→Method, Goals 3-5→Cross-Cutting), Foundation/Baccalaureate 2단계 발달 모델은 1-4학년 연구 파이프라인(N1→N3→E10→N4)과 직접 정렬된다. APA/BPS/EuroPsy/APAC/ICUP 국제 인증 표준이 공통적으로 독립적 실증 연구 수행 필수, EDI 교과과정 내재화, 오픈사이언스/신통계 반영을 강화하고 있다. 심리학-데이터사이언스 융합 교과과정이 Northeastern, Stanford, UPenn, UW-Madison 등에서 제도화되어 N2/N3 신설의 글로벌 벤치마크를 제공한다.

**한국 정책 정합성**: 교육부의 AI 인재양성 부트캠프 예산 25배 증가(23억→570억), 전 생애주기 AI 보편교육, AX대학원 2030년 22개교 확대(연간 820명), KAIST AI College 2026 개설, 대학혁신지원사업(2025-2027, 138개 대학, 1.76조원) 등은 Inno-Edu 2031 사업의 국가 정책 정합성이 매우 높음을 보여준다. 고려대학교의 62년 만의 심리학 독립학부 전환(2021)과 5대 혁신 사회주제(Mind & Machine 등) 중심 교과 재편은 국내 심리학 교육 혁신의 직접적 선례이다.

#### 3.3.7 B7 측정·평가

B7 분기는 70편(P0 6편, P1 30편, P2 20편, P3 14편; Tier 1 84.3%)을 종합하여 12개 핵심 발견을 도출하였다. 강 6개, 중 6개이다.

**학습 성과 측정 도구**: SOLO Taxonomy(Biggs & Collis, 1982/2014)는 학습 반응의 구조적 복잡성을 5단계로 분류하는 내용 영역 독립적(domain-independent) 체계로, BMBM 4대 모듈 전체에 적용 가능한 범용 평가 프레임워크이다. SOLO 기반 혼합 평가 모형이 자기조절학습 향상에 효과적이며, 형성적 평가의 반복적 적용이 기초 지식 구조에서 복합 지식 구조로의 전환을 촉진한다. AI 리터러시 측정에서는 Ng et al.(2024)의 AILQ(ABCE 4차원, 32문항)가 유력한 표준 도구로 부상하고 있으나, 교차문화 타당도를 검증한 척도는 전무하여 한국어 버전 개발이 필요하다. K-DOCS(Kaufman et al., 2012; 5개 창의성 영역, alpha .904, 22,013명 규준)와 CAT(전문가 합의 기반 평정, alpha .80-.90)는 PBL 창의성 평가의 상호 보완적 표준 도구로 확인되었다.

**GenAI 시대 평가 재설계와 학술 무결성**: 평가 재설계는 AI 탐지보다 설계를 통해 무결성을 달성해야 한다는 강력한 합의가 형성되었다. AIAS(AI Assessment Scale) Version 2는 5단계 GenAI 통합 수준을 제시하며 전 세계 수백 개 기관에서 채택되었고, AAAE(Against-Avoid-Adopt-Explore) 프레임워크는 과목별 차등 AI 정책 설계의 근거를 제공한다. AI 저항적 평가의 5대 유형(반복적 프로젝트, 성찰적 글쓰기, 구술 평가, 실시간 문제해결, 동료 상호평가)이 식별되었다. ICAI 보고에 따르면 58%의 학생이 AI 도구를 활용한 부정직한 과제 완성 경험이 있으나, 처벌 중심 접근의 한계가 실증되어 AI 리터러시 교육과 연계된 무결성 문화 조성이 근본적 해결책으로 제시되었다.

**거버넌스와 학생 참여**: 네덜란드 3개 의과대학 연구에서 분산형 거버넌스(만족감+불완전 변화)와 하향식(성공적 구현+교수 탈동기)의 장단점이 확인되었으며, "포용적 거버넌스(inclusive governance)"가 "공유 거버넌스"보다 적절한 개념으로 제안되었다(Burm et al., 2024). 학생 참여는 정보 제공→자문→참여→파트너십의 4단계 중 파트너십이 가장 효과적이나 구현이 가장 어려우며, 형식적 대표성(tokenism)을 넘는 실질적 참여 구조가 필요하다. 한국 20개 대학 AI 가이드라인 분석에서 학습자 영역(44%)과 교수자 영역(37%)은 상당수가 다루나, 연구자 영역(21%)과 실무자 영역(7%)은 현저히 낮아 보완이 필요하다.

### 3.4 교차 분기 주제

7개 분기별 종합 결과를 교차 분석한 결과, 다음의 교차 분기 주제(cross-cutting themes)가 도출되었다.

**PBL × AI 통합**: B3(PBL)과 B2(AI)의 교차 영역에서, AI 도구가 PBL 수업의 효과를 증폭할 가능성과 동시에 학습 과정의 진정성을 훼손할 위험이 동시에 확인되었다. GenAI의 안내된 사용(scaffolded use)이 비안내 사용 대비 0.83 더 큰 효과를 보인다는 B2의 발견은, B3의 PBL 수업에서 AI 도구를 구조화된 프롬프트 가이드라인과 함께 활용해야 함을 시사한다. B7의 AAAE 프레임워크와 AIAS 5단계는 PBL 과제별로 AI 통합 수준을 차등 설정하는 실무적 도구를 제공한다. Brain-Mind-Behavior Studio에서 이 통합이 시범 적용될 수 있다.

**연구 파이프라인 × 윤리**: B4(학부 연구)와 B2(AI 도구), B7(거버넌스)의 교차 영역에서, 학부생의 AI 도구 활용 연구에서 데이터 프라이버시, 알고리즘 편향, 재현성 문제가 새로운 윤리적 의사결정 영역으로 부상하였다. Katsarov et al.(2022)의 연구윤리 교육 메타분석(B4), FAIR 원칙 기반 RDM 교육(B4), Chan(2023)의 AI 정책 3차원 모델(B7)이 통합적으로 적용되어야 한다. N1(연구 입문)에서의 연구윤리 교과 내 통합과 N2(AI)에서의 AI 윤리 모듈은 이 교차 영역의 직접적 교과과정 대응이다.

**형평성(equity) 관통 주제**: 능동학습의 성취 격차 축소(B3, 시험점수 33%, 합격률 45%), URP의 형평성 격차 완전 해소(B4, Krim et al. 120,308명), CURE의 형평성 기반 접근(B4), EDI의 교과과정 구조적 내재화(B6, APA/BPS/APAC 공통 강화)가 분기 간 일관되게 확인된다. Theobald et al.(2020)의 발견 — 고강도 능동학습(67%+)만이 유의미 — 은 PBL 비중 목표를 50%에서 추후 67% 이상으로 상향하는 장기 근거를 제공한다.

**교수 개발 × 평가 재설계**: B5(교수 역량)의 TPACK-AI 프레임워크와 B7(평가)의 GenAI 시대 평가 재설계는 불가분하게 연결된다. 교수의 AI 리터러시와 평가 재설계 역량이 동시에 개발되어야 하며, AI Teaching Bootcamp에 평가 재설계 모듈을 필수 포함해야 한다는 발견은 B5와 B7 양쪽에서 수렴한다. SOLO 기반 루브릭 적용에서 교수자 훈련이 신뢰도 확보의 핵심 조건이라는 점(B7)도 교수 개발과 평가의 교차 지점이다.

**오픈사이언스 × 전 교과과정 통합**: 재현성 혁명의 구조적·절차적·공동체 차원 변화(B2, Korbmacher et al., 2023)는 B1(교과 설계), B4(연구 훈련), B7(평가 도구)에 걸쳐 교과과정 전반에 오픈사이언스 실천을 내재화할 필요성을 제기한다. Frank et al.(2025)의 Experimentology 교재, Markant & Galati(2023)의 OSCI(오픈사이언스 개념 목록)는 이 통합의 구체적 교육 자원이다.

### 3.5 교과과정 매핑 결과 요약

600편의 근거를 14개 개편 과목(신설 4개 + 강화 개편 10개)에 매핑한 결과, 14개 과목 모두 5편 이상의 직접 근거를 확보하였다(최소 18편, 최대 37편). 전체 약 397편의 고유 매핑이 확인되었다.

**14과목 × 7분기 매트릭스**: 각 과목별로 핵심(●), 부분(◐), 간접(○) 연계도를 평가한 결과, 신설 4개 과목(N1-N4)은 Method 모듈에 배치되어 B4(학부 연구)와 B2(AI·데이터)가 핵심 분기로 작용한다. 강화 개편 과목 중 E1(심리통계), E2(실험심리), E9(심리측정)는 Method 모듈로서 B2와 B7이 핵심이며, E3(인지과정), E4(임상신경), E10(뇌이미징DS)은 Brain 모듈로서 B1이 핵심이다. E5(발달), E6(사회), E7(조직), E8(임상)은 Behavior 모듈로서 B1과 B2가 핵심이다.

**BMBM 모듈별 근거 분포**: Brain 모듈(3과목, ~92편, 평균 30.7편/과목), Behavior 모듈(4과목, ~116편, 평균 29.0편/과목), Method 모듈(7과목, ~189편, 평균 27.0편/과목)로, 전 모듈에 걸쳐 충분한 근거 기반이 확보되었다.

**핵심 변환 내용**: 신설 과목에서 N1(연구 입문)은 AI 문헌검색, 연구윤리, 데이터 리터러시를, N2(심리과학 AI)는 Python ML/NLP와 영역별 AI 활용을, N3(심리데이터 분석)은 R/Python 데이터분석과 재현 가능 워크플로우를, N4(캡스톤)는 전체 연구 파이프라인과 3트랙 졸업논문을 핵심 내용으로 설정한다. 강화 개편 과목에서는 E1의 수기 계산→R/Python 40%, E2의 전통 실험→PsychoPy/jsPsych, E3의 전통 인지→AI 인지 모델링, E10의 기초→딥러닝 뇌영상 등이 주요 변환 방향이다.

### 3.6 APA Goals 매핑 결과

APA Guidelines 3.0의 5대 학습 목표와 4대 Cross-Cutting Integrative Themes를 14개 과목에 매핑한 결과(14과목 × 9항목 = 126셀 전수 매핑), 다음의 패턴이 확인되었다.

**Goal별 핵심 교과 분포**: Goal 1(Knowledge Base)은 N1, E3-E10의 9개 과목에서 핵심(●) 연계되어 가장 넓은 커버리지를 보인다. Goal 2(Scientific Inquiry)는 N2, N3, E1, E2, N4의 5개 Method 모듈 과목에서 핵심 연계된다. Goal 3(Ethics/Values)는 N1, N4, E8에서 핵심 연계되며, Goal 4(Communication)는 N4에서만 핵심 연계되어 가장 약한 커버리지를 보인다. Goal 5(Professional Development)는 N4, E7, E8에서 핵심 연계된다.

**Cross-Cutting Themes 커버리지**: Theme 2(Technology Integration)는 11개 과목에서 강한 연계를 보여 가장 높은 커버리지를 달성하였다. Theme 3(Application)는 8개 과목, Theme 1(DEI)과 Theme 4(Global/Sociocultural)는 각 4개 과목에서 강한 연계를 보인다.

**약한 영역 및 보완 권고**: (1) Goal 4(Communication)는 N4 외 독립 교과가 부재하여 E2/E6에 학술 발표 요소를 강화할 필요가 있다. (2) Goal 5(Professional Development)는 N4 외 약하여 인턴십/진로 세미나 연계가 필요하다. (3) Theme 1(DEI)은 Brain 모듈에서 약하여 신경다양성 관점 추가가 필요하다. (4) Theme 4(Global/Sociocultural)는 전반적으로 제한적이어서 B6 벤치마크 연계 강화가 필요하다.

---

## 4. 논의

### 4.1 근거 종합: BMBM 교과과정의 학술적 정당성

본 범위 검토의 600편 근거 종합은 서울대학교 심리학과 BMBM 교과과정 개편의 학술적 정당성을 다층적으로 뒷받침한다.

**교수법 혁신의 근거 강도**: PBL/능동학습 분기(B3)는 가장 강력한 근거 기반을 보유하고 있다. Freeman et al.(2014, 7,600+ 인용)의 랜드마크 메타분석, Schneider et al.(2025)의 2차 메타분석(ES = 0.60), Theobald et al.(2020)의 형평성 메타분석, 국내 116편 PBL 메타분석(박하은 외, 2023) 등 22편의 메타분석이 PBL 비중 확대의 정당성을 확립한다. 특히 Theobald et al.이 보고한 "고강도 능동학습(67%+)만이 성취 격차 축소에 유의미"하다는 발견은, 현행 목표(50%)가 형평성 관점에서는 중간 단계이며 장기적으로 67% 이상을 지향해야 함을 시사한다.

**AI 통합 교육의 근거**: GenAI의 학습 성과 효과(g = 0.68)와 안내된 사용의 우월성(+0.83), ITS 메타분석의 긍정적 효과(g = 0.42-0.86), 심리학 특화 데이터사이언스 교과과정의 글로벌 확산은 N2(심리과학을 위한 AI)와 N3(심리데이터 분석 I) 신설의 시의성을 확인한다. 다만 GenAI의 상위 인지(창작, 평가)에 대한 효과가 미미하다는 발견은, AI 도구가 교수법을 대체하는 것이 아닌 보완하는 방식으로 통합되어야 함을 강조한다.

**연구 파이프라인의 근거**: 120,308명 대규모 실증(Krim et al., 2024)에서 URP의 졸업률 향상과 형평성 격차 해소 효과, CURE 5차원 설계 원리(Auchincloss et al., 2014), 국내 캡스톤 효과크기 0.96(허미선 & 이정민, 2021)은 N1-N4 연구 파이프라인의 설계 근거로서 매우 강력하다. 10주 연구지도 프로그램의 멘토링 구조화, Harvard CUHS 모델의 IRB 훈련, ePortfolio 기반 종단 평가 등 운영 수준의 근거도 충분히 확보되었다.

### 4.2 한국 맥락의 특수성

본 리뷰는 54편(9.0%)의 한국어 소스를 포함하여 한국 고등교육 맥락의 특수성을 체계적으로 반영하였다.

**정책 환경**: 교육부의 AI 인재양성 정책(부트캠프 예산 25배 증가), 대학혁신지원사업(1.76조원), AX대학원 확대 등은 Inno-Edu 2031 사업에 유리한 정책 환경을 형성한다. 서울대학교 자체적으로도 2025학년도 교양교과과정 전면 개편, 첨단융합학부 설립, 데이터사이언스대학원(GSDS)의 ABCDE 원리 교육 등이 BMBM 교과과정과 시너지를 창출할 기반을 제공한다.

**국내 실증 근거**: 116편 국내 PBL 메타분석에서 사회과학 PBL 효과가 상위권으로 확인되었으며, 국내 캡스톤 메타분석(효과크기 0.96)이 졸업논문 3트랙의 근거를 제공한다. 가천대의 60명 60시간 AI 교수 부트캠프(1인당 500만원 강의개발비), 대교협의 약 50개 AI 교수법 과정 등은 AI Teaching Bootcamp 설계의 국내 참조 모델이다.

**고유한 과제**: 한국 심리학과 URP 직접 사례, AI 보조 연구윤리 가이드라인, 졸업논문 3트랙 간 비교 효과 실증, 학부생 연구 자기효능감의 문화적 맥락, 심리학과 특화 AI 교수 개발 사례 등은 잔여 지식 갭으로 식별되었다. 이러한 갭은 1차년도 시범 운영을 통한 자체 근거 축적과 한국심리학회 산하 학과 현황 조사를 통해 보완되어야 한다.

### 4.3 한계

본 범위 검토는 다음의 한계를 가진다.

첫째, **AI 보조 검색의 구조적 한계**이다. 전통적 체계적 리뷰와 달리 AI 에이전트를 활용한 검색 전략은 데이터베이스별 정확한 히트 수와 제외 사유의 상세 기록이 어려워, PRISMA 흐름도에서 추정 범위로 제시하였다. 이는 결과의 완전한 재현 가능성을 제한한다.

둘째, **심리학 전공 특화 실증 근거의 부족**이다. PBL, 능동학습, FLC 등의 효과에 관한 메타분석은 STEM 전반 또는 고등교육 일반을 대상으로 한 것이 대부분이며, 심리학 전공 교육에 직접 적용한 실증 연구는 상대적으로 제한적이다. B3의 Playfoot(2023)이 심리학 학부 통계 모듈에서의 직접 적용을 보고한 것은 예외적 사례이다.

셋째, **한국어 소스의 학술적 다양성 제한**이다. 54편의 한국어 소스 중 상당수가 정책 문서, 기관 보고서, KCI 등재 논문으로서 국제 peer-reviewed 저널 대비 방법론적 엄밀성에 차이가 있을 수 있다.

넷째, **질적 평가의 심도**이다. 600편의 대량 문헌을 AI 보조로 처리함에 따라, 개별 연구의 내적 타당도, 외적 타당도, 편향 위험에 대한 심층 비판적 평가가 전통적 체계적 리뷰 수준에는 미치지 못할 수 있다.

다섯째, **출판 편향**이다. 긍정적 결과를 보고하는 연구가 과대대표되었을 가능성이 있으며, 특히 PBL과 AI 교육 효과에 관한 메타분석에서 이 문제가 내재할 수 있다.

### 4.4 교과과정 혁신 시사점

본 리뷰의 근거 종합에 기반하여, BMBM 교과과정 혁신의 핵심 시사점을 다음과 같이 제시한다.

**BMBM 모듈 설계 원칙**: 모듈 내 수직적 심화(Intro→Intermediate→Advanced)와 모듈 간 수평적 교차를 동시에 설계해야 하며(B1), 각 모듈의 학습 성과를 APA 3.0 Foundation/Baccalaureate 2단계에 정렬하고(B6), SOLO Taxonomy 기반 범용 평가 루브릭으로 통일된 성과 추적 체계를 구축해야 한다(B7).

**PBL 확대 전략**: 4-5명 소그룹, 9-18주 기간이 최적이며(B3), 교수자 주도 형성적 평가(ES = +0.41)가 효과의 핵심 조건이다(B7). 현행 50% 목표는 형평성 관점에서 중간 단계이며, 2차년도 이후 67% 이상 목표 상향을 검토해야 한다(B3).

**AI 통합 원칙**: GenAI 활용 시 구조화된 scaffolding이 필수이며(B2), 과목별 AIAS 5단계 차등 적용(B7), AI Teaching Bootcamp를 통한 교수 역량 동시 개발(B5), AI 저항적 평가 5대 유형의 과목별 적용(B7)이 핵심이다.

**연구 파이프라인 구축**: N1(1학년)→N3(2학년)→E10(4학년)→N4(4학년)의 종단적 연구 역량 발달 경로를 Healey & Jenkins(2009)의 4사분면 모형(Research-led→Research-based)에 정렬하고(B4), 10주 연구지도 프로그램에 Linn(2015)의 5가지 멘토링 기능을 체계화하며(B4), 연구윤리 교육을 교과과정 내 통합 형태로 포함해야 한다(B4).

**교수 개발 3단계**: AI Teaching Bootcamp(단기 집중, TPACK-AI 기반)→Teaching Innovation Pods(장기 FLC, Cox 모델)→기관 거버넌스(심리학혁신위원회, 인센티브 구조)의 3단계 통합 모델이 근거에 기반한다(B5).

### 4.5 향후 연구 방향

본 범위 검토에서 식별된 잔여 지식 갭에 기반하여, 다음의 후속 연구를 권고한다.

첫째, **1차년도 시범 운영의 체계적 평가 연구**이다. PBL 시범 과목, AI Teaching Bootcamp, 10주 연구지도 프로그램의 효과를 Kirkpatrick 4단계 모델(반응-학습-행동-결과)로 평가하고, SRA/K-DOCS/SOLO 루브릭을 활용한 사전-사후 설계를 구축하여 자체 근거를 축적해야 한다.

둘째, **한국어 평가 도구의 번안·타당화**이다. SRA(통계적 추론), AILQ(AI 리터러시), SRSE(연구 자기효능감)의 한국어 번안과 서울대 학부생 표본에서의 심리측정적 속성 검증이 선행 과제이다.

셋째, **심리학과 특화 AI 교수 개발 효과 연구**이다. AI Teaching Bootcamp의 TPACK-AI 역량 변화, 교수 프로파일별 차별화된 훈련 효과, Bootcamp→TIP 전환의 교수법 변화 지속성을 종단적으로 추적하는 연구가 필요하다.

넷째, **졸업논문 3트랙 간 비교 효과 연구**이다. 실험 연구, 데이터 분석 프로젝트, 비판적 문헌 리뷰 트랙 각각의 학습 성과, 연구 자기효능감, 대학원 진학률을 비교하는 준실험 설계가 권장된다.

다섯째, **AI 보조 연구윤리 교육 모델 개발**이다. 학부생이 AI 도구를 연구에 활용할 때의 윤리적 의사결정 가이드라인은 현재 문헌에서 공백으로 확인되었으며, 서울대 심리학과가 선도적으로 개발할 수 있는 영역이다.

---

## 5. 결론

본 범위 검토는 7개 학술 데이터베이스, 2개 한국어 데이터베이스, grey literature를 대상으로 4단계 반복적 검색을 수행하여 600편의 근거를 종합하였다. 7개 분기, 29개 하위분기, 97개 리프 카테고리에 걸쳐 100% 커버리지를 달성하였으며, Tier 1 비율 72.2%, 2020년 이후 출판물 약 87%, 한국어 소스 54편(9.0%)의 분포를 확보하였다.

서울대학교 심리학과 Inno-Edu 2031 사업의 BMBM 교과과정 개편은 다음의 핵심 근거에 의해 학술적으로 정당화된다.

첫째, **PBL/능동학습의 효과는 22편의 메타분석에 의해 가장 강력하게 뒷받침된다.** PBL 전체 효과크기 0.44-0.64, 능동학습의 성취 격차 축소 33-45%, 한국 대학 맥락에서의 PBL 효과(사회과학 상위권), 플립드 클래스룸 효과(g = 0.726) 등은 PBL 비중 13%→50% 확대의 학술적 정당성을 확립한다.

둘째, **AI·데이터 교육 통합은 시의적절하며, 구조화된 접근이 필수적이다.** GenAI 학습 효과(g = 0.68), 안내된 사용의 우월성(+0.83), 심리학-데이터사이언스 융합 교과과정의 글로벌 확산, 오픈사이언스의 제도적 전환은 N2/N3 신설의 근거를 제공한다.

셋째, **학부생 연구 파이프라인은 형평성과 효과 양면에서 강력한 근거를 보유한다.** URP의 형평성 격차 완전 해소(120,308명 실증), CURE 5차원 설계 원리, 국내 캡스톤 효과크기 0.96, 체계적 멘토링의 10가지 실천은 N1-N4 연구 파이프라인의 설계 기반이다.

넷째, **교수 역량 개발은 3단계 통합 모델(Bootcamp→FLC→거버넌스)로 설계되어야 한다.** TPACK-AI 프레임워크, FLC 종료 후 2년 지속 효과, 4대 장벽 대응 전략, SoTL Teaching Commons 비전이 근거이다.

다섯째, **국제 표준 정렬과 한국 정책 정합성이 동시에 확보된다.** APA 3.0/BPS/EuroPsy/APAC/ICUP의 수렴적 인증 표준, 한국 교육부의 AI 인재양성 정책, 서울대 내부 교과과정 혁신 생태계는 BMBM 교과과정이 국제적으로 정렬되면서 국내 정책 환경에도 부합함을 보여준다.

14개 과목별 근거 매핑(약 397편), APA 학습목표 정렬 매트릭스(126셀), Top 50 핵심 소스 선정을 통해 교과과정 개편의 구체적 실행 방향이 제시되었다. 1차년도(2026.3-12) 시범 운영 과정에서 체계적 평가 연구를 병행하여 자체 근거를 축적하고, 잔여 지식 갭을 보완하는 것이 향후 과제이다.

---

## 참고문헌

본 참고문헌은 보고서 본문에서 직접 인용된 핵심 소스 50편을 중심으로 제시한다. 전체 600편의 상세 서지정보는 분기별 종합 보고서(`B1_synthesis.md`-`B7_synthesis.md`)에 수록되어 있다.

### B1 BMBM 교과과정 설계

1. APA Board of Educational Affairs. (2023). *APA Guidelines for the Undergraduate Psychology Major: Version 3.0*. APA. https://www.apa.org/about/policy/undergraduate-psychology-major
2. Frank, M.C. et al. (2025). *Experimentology: An Open Science Approach to Experimental Psychology Methods*. MIT Press. https://experimentology.io/
3. Field, A. et al. (2025). *Discovering Statistics Using JASP*. SAGE. https://profandyfield.com/discoverse/dsuj/
4. Thibault, R.T. et al. (2024). A Delphi study to strengthen research-methods training in psychology. *AMPPS*, 7(1). https://doi.org/10.1177/25152459231213808
5. Chen, A. et al. (2023). Community-derived core concepts for neuroscience higher education. *CBE-Life Sciences Education*. https://doi.org/10.1187/cbe.22-02-0018
6. Peirce, J. et al. (2019/2022). PsychoPy2: Experiments in behavior made easy. *Behavior Research Methods*, 51, 195-203. https://doi.org/10.3758/s13428-018-01193-y
7. Coley, J.D. & Tanner, K.D. (2019). Implementing cognitive science in undergraduate science. *CBE-Life Sciences Education*, 18(4), es10. https://doi.org/10.1187/cbe.18-12-0240
8. Tahirsylaj, A. & Sundberg, D. (2025). Five visions of competence-based education. *Journal of Curriculum Studies*. https://doi.org/10.1080/00220272.2025.2492605
9. Wiertelak, E.P. et al. (2018). The new blueprints: Undergraduate neuroscience education. *JUNE*, 17(1), A20-A25. https://pmc.ncbi.nlm.nih.gov/articles/PMC6153019/

### B2 AI·데이터 기반 연구 방법론

10. Open Science Collaboration. (2015). Estimating the reproducibility of psychological science. *Science*, 349(6251), aac4716. https://doi.org/10.1126/science.aac4716
11. Ma, S. et al. (2025). A meta-analysis of the impact of GenAI on learning outcomes. *Journal of Computer Assisted Learning*. https://doi.org/10.1111/jcal.70117
12. Ma, W. et al. (2014). Intelligent tutoring systems and learning outcomes: A meta-analysis. *Journal of Educational Psychology*, 106(4), 901-918. https://doi.org/10.1037/a0037123
13. Korbmacher, M. et al. (2023). The replication crisis has led to positive structural, procedural, and community changes. *Communications Psychology*, 1(1), Article 3. https://doi.org/10.1038/s44271-023-00003-2
14. Navarro, D.J. et al. (2022+). *Learning Statistics with JASP*. https://learnstatswithjasp.com/
15. Markant, D.B. & Galati, A. (2023). Development of a concept inventory on open and transparent research. *Collabra: Psychology*, 9(1). https://doi.org/10.1525/collabra.75226
16. Cushman, F. (2024). Computational social psychology. *Annual Review of Psychology*, 75, 625-652. https://doi.org/10.1146/annurev-psych-021323-040420
17. University of Glasgow PsyTeachR Team. (2024). *Reproducible research in R for psychology*. https://psyteachr.github.io/

### B3 PBL 및 수업방법 혁신

18. Freeman, S. et al. (2014). Active learning increases student performance in science, engineering, and mathematics. *PNAS*, 111(23), 8410-8415. https://doi.org/10.1073/pnas.1319030111
19. Theobald, E.J. et al. (2020). Active learning narrows achievement gaps for underrepresented students. *PNAS*, 117(12), 6476-6483. https://doi.org/10.1073/pnas.1916903117
20. Schneider, M. et al. (2025). The effect of problem-based learning approach on learning outcomes: A second-order meta-analysis study. *Educational Research Review*. https://doi.org/10.1016/j.edurev.2025.100668
21. Kozanitis, A. & Nenciovici, L. (2023). Effect of active learning in humanities and social sciences: A meta-analysis. *Higher Education*, 86, 1377-1394. https://doi.org/10.1007/s10734-022-00977-8
22. Zhang, L. & Ma, Y. (2023). A study of the impact of project-based learning on student learning effects: A meta-analysis. *Frontiers in Psychology*, 14, 1202728. https://doi.org/10.3389/fpsyg.2023.1202728
23. Playfoot, D. (2023). Flipped classrooms in undergraduate statistics: Online works just fine. *Teaching of Psychology*. https://doi.org/10.1177/00986283211046319
24. 박하은 외. (2023). 국내 대학 문제중심학습(PBL)의 학습 효과에 대한 메타분석. *학습자중심교과교육연구*, 23(6), 557-. https://doi.org/10.22251/jlcci.2023.23.6.557

### B4 학부생 연구역량 파이프라인

25. Lopatto, D. (2010). Undergraduate research as a high-impact student experience. *Peer Review*, 12(2), 27-30.
26. Linn, M.C. et al. (2015). Undergraduate research experiences: Impacts and opportunities. *Science*, 347(6222), 1261757. https://doi.org/10.1126/science.1261757
27. Krim, J.S. et al. (2024). URP reduces equity gaps in STEM graduation. *CBE-Life Sciences Education*. https://doi.org/10.1187/cbe.22-03-0061
28. Shanahan, J.O. et al. (2015). Ten salient practices of undergraduate research mentors. *Mentoring & Tutoring*, 23(5), 359-376. https://doi.org/10.1080/13611267.2015.1126162
29. Auchincloss, L.C. et al. (2014). Assessment of CUREs: A meeting report. *CBE-Life Sciences Education*, 13(1), 29-40. https://doi.org/10.1187/cbe.14-01-0004
30. Katsarov, J. et al. (2022). Effective strategies for research integrity training: Meta-analysis. *Educational Psychology Review*, 34, 935-971. https://doi.org/10.1007/s10648-021-09630-9
31. 허미선 & 이정민. (2021). 국내 캡스톤 디자인 교육의 학습효과에 관한 메타분석. KCI ART002711246.

### B5 교수역량 강화

32. Mishra, P. & Koehler, M.J. (2006). Technological pedagogical content knowledge: A framework for teacher knowledge. *Teachers College Record*, 108(6), 1017-1054. https://doi.org/10.1111/j.1467-9620.2006.00684.x
33. Cox, M.D. (2004). Introduction to faculty learning communities. *New Directions for Teaching and Learning*, 97, 5-23. https://doi.org/10.1002/tl.129
34. Stanford Center for Teaching and Learning. (2024-present). AIMES: AI Meets Education at Stanford. https://ctl.stanford.edu/aimes
35. Derek Bok Center for Teaching and Learning, Harvard University. (2023-present). Teaching and AI Resources. https://bokcenter.harvard.edu/teaching-ai
36. Brownell, S.E. & Tanner, K.D. (2012). Barriers to faculty pedagogical change. *CBE-Life Sciences Education*, 11(4), 339-346. https://doi.org/10.1187/cbe.12-09-0163
37. Tomkin, J.H. et al. (2019). Sustaining pedagogical change via faculty learning communities. *International Journal of STEM Education*, 6, Article 26. https://doi.org/10.1186/s40594-019-0180-5

### B6 글로벌 벤치마크 및 정책

38. Chan, C.K.Y. (2023). A comprehensive AI policy education framework for university teaching and learning. *IJETHE*, 20, Article 38. https://doi.org/10.1186/s41239-023-00408-3
39. 교육부. (2025-2026). 한국 고등교육 혁신 정책: 2026 업무계획 및 2025-2027 대학혁신지원사업.
40. 고려대학교 심리학부. (2021). 독립학부 전환 및 교과과정 개편.
41. APA IPI Working Group. (2024). *Introductory Psychology Initiative: Student Learning Outcomes and Five Pillars Framework*. APA.
42. Cranney, J. et al. (2025). Collaborative processes in the development of the ICUP Model. *International Journal of Psychology*, 60(4). https://doi.org/10.1002/ijop.70061
43. NUS CTLT. (2024). *Policy for Use of AI in Teaching and Learning*. NUS.

### B7 측정·평가·거버넌스

44. Biggs, J.B. & Collis, K.F. (1982/2014). *Evaluating the Quality of Learning: The SOLO Taxonomy*. Academic Press.
45. Perkins, M. et al. (2024/2025). AI Assessment Scale Revisited (AIAS v2). *JUTLP*. arXiv:2412.09029.
46. Long, D. & Magerko, B. (2020). What is AI literacy? Competencies and design considerations. *CHI '20*, 1-16. https://doi.org/10.1145/3313831.3376727
47. Kaufman, J.C. et al. (2012). Counting the Muses: Development of K-DOCS. *Psychology of Aesthetics, Creativity, and the Arts*, 6(4), 332-340.
48. 교육부·대교협. (2024-2025). 대학 인공지능 활용 윤리 가이드라인 시안.

### 추가 핵심 소스

49. Saragosa-Harris, N.M. et al. (2022). A practical guide for the ABCD Study and large longitudinal datasets. *Developmental Cognitive Neuroscience*, 55. https://doi.org/10.1016/j.dcn.2022.101115
50. Healey, M. & Jenkins, A. (2009). *Developing Undergraduate Research and Inquiry*. HE Academy.

---

> **보고서 작성 완료**: 2026-03-13
> **방법론**: PRISMA-ScR + Arksey & O'Malley (2005) + JBI Manual PCC
> **총 근거**: 600편 (7개 분기, 29개 하위분기, 97개 리프, 100% 커버리지)
> **Top 50 핵심 소스**: Tier 1 82%, 메타분석 13편(26%), 한국 맥락 6편(12%)
> **14과목 매핑**: 약 397편 고유 매핑 | APA Goals 126셀 전수 매핑
