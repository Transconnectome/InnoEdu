# B2 근거 종합 보고서: AI·데이터 기반 연구 방법론

## 개요

본 보고서는 서울대학교 심리학과 교육혁신 사업(Inno-Edu 2031)의 600편 Scoping Review 중 B2 분기(AI·데이터 기반 연구 방법론) 100편에 대한 근거 종합(evidence synthesis)이다. B2.1(AI in Psychology Education), B2.2(데이터 사이언스), B2.3(Python/R 실습), B2.4(연구 파이프라인 AI) 4개 하위분기, 15개 리프 카테고리의 핵심 발견을 교차 분석하여 교과과정 개편에 대한 실행 가능한 시사점을 도출한다.

| 항목 | 내용 |
|------|------|
| 분기 | B2 — AI·데이터 기반 연구 방법론 |
| 총 소스 수 | 100편 (P0: 10, P1: 30, P2: 25, P3: 35) |
| Tier 1 비율 | 77.0% |
| 근거 강도 분포 | 강 29편, 중 48편, 약 23편 |
| 종합 일자 | 2026-03-13 |
| 관련 교과목 | N2 심리과학을 위한 AI, N3 심리데이터 분석I, E1 심리통계학, E10 뇌이미징 DS |

---

## 연구 질문

1. LLM/GenAI를 심리학 교육에 효과적으로 활용하는 방법은 무엇인가?
2. 데이터 사이언스 교육과정을 심리학에 어떻게 최적화할 수 있는가?
3. Python/R 코딩 교육의 비전공자 대상 효과적 교수법은 무엇인가?
4. 연구 파이프라인 전 과정에 AI를 어떻게 통합할 수 있는가?

---

## 하위분기별 핵심 발견

### B2.1 AI in Psychology Education (34편)

#### 발견 1: GenAI는 심리학 교육에서 중간~큰 긍정적 효과를 보이나, 안내된 사용(instructed use)이 핵심 조건이다

- **근거 강도: 강** (메타분석 4편, RCT 2편)
- Ma et al. (2025, P3-S007): GenAI 전체 학습 성과 통합 효과 크기 g=0.68 (p<0.001). 안내된 사용이 비안내 사용 대비 효과 크기 0.83 더 큰 것으로 확인
- ChatGPT 학부생 메타분석 (P3-S008): Hedges' g=1.14 (SE=0.185)의 큰 긍정적 효과
- 69편 실험연구 메타분석 (P3-S006): ChatGPT가 학업 성과, 정의적-동기적 상태, 고차 사고력 향상에 기여
- GenAI 고차 사고력 메타분석 (P3-S035): 29개 실험/준실험 분석, 안내된 사용 조건에서 유의미하게 더 큰 효과
- **시사점**: N2 과목에서 ChatGPT/LLM 활용 시 구조화된 프롬프트 가이드라인과 교수 설계(scaffolding)가 필수적. 비안내 자유 사용은 효과 크기 감소 및 비판적 사고 저해 위험

#### 발견 2: AI 튜터링 시스템은 전통적 교수법 대비 유의미한 학습 효과를 보이며, 심리학 교육에 적용 가능하다

- **근거 강도: 강** (메타분석 2편, RCT 2편, 체계적 리뷰 1편)
- Ma et al. (2014, P3-S003): ITS 메타분석(107 효과크기, 14,321명) — 교사 주도 수업 대비 g=0.42, 비ITS 컴퓨터 대비 g=0.57, 교과서 대비 g=0.35
- P2-B2-003: 30개 연구 메타분석 — ITS 전체 효과크기 g=0.86
- Kestin et al. (2025, P3-S001): Harvard RCT(N=194) — AI 튜터가 교실 내 능동적 학습 대비 유의미하게 높은 성과
- DeepMind LearnLM (P3-S028): 감독된 AI 튜터링이 인간 튜터링과 비교 가능한 성과 달성
- P1-B2-006: 감정 지능형 ITS가 학생 성과 평균 20% 향상
- **시사점**: BMBM 모듈 전반에 AI 튜터 도입의 근거 확보. 특히 Method 모듈에서 통계·코딩 학습 보조 도구로 AI 튜터 시범 도입 가능

#### 발견 3: AI 리터러시는 다차원 역량으로, 심리학 고유의 프레임워크 내에서 교육해야 한다

- **근거 강도: 중** (체계적 리뷰 3편, 프레임워크 개발 3편, 측정도구 리뷰 1편)
- P1-B2-004: 10년간 서지분석 — AI 리터러시 핵심 요소: AI 인식/이해, AI 사용/응용, AI 평가/창조, AI 윤리 이해
- Ng et al. (2024, P2-B2-002): AILQ 32문항 검증 — 정의적·행동적·인지적·윤리적 4차원
- Lintner (2024, P2-B2-001): 16개 AI 리터러시 척도 리뷰 — 대부분 구조 타당도만 검증, 문화 간 타당도 부재
- APA (S17): 심리학자를 위한 AI 역량을 3대 도메인으로 정의
- OECD/EC (P3-S015), UNESCO (P3-S030): 국제 AI 리터러시 프레임워크 개발 진행 중
- 독일 사례 (P1-B2-004): 대학의 31.6%만 AI 리터러시를 명시적으로 교육
- **시사점**: N2 과목은 범용 AI 리터러시가 아닌 심리학 연구·실천 맥락의 AI 역량을 목표로 설계해야 함. 기존 AI 리터러시 척도의 심리학 적용 타당화 연구 필요

#### 발견 4: AI 윤리 교육은 독립 과목보다 교과과정 전반에 내재화(embedding)해야 하며, 한국 맥락의 고유 과제가 존재한다

- **근거 강도: 중** (체계적 리뷰 4편, 실증 연구 2편, 한국어 소스 2편)
- P3-S012: 68편 체계적 리뷰 — AI 윤리 교육의 교과과정 내재화 여전히 제한적
- P2-B2-004: 기술-교육-사회 3차원 윤리 리스크 분류
- Baker & Hawn (2022, P2-B2-007): 인종·성별·국적·SES 등 다양한 편향 유형 분류
- P3-S032: 한국 대학 AI 윤리교육 현황 — 주로 선택/교양과목, 강의식 중심 운영
- P3-S033: 서울 소재 대규모 국립대학교 593명 대학원생 — 안전성·책임성·투명성·인권보장이 우선 교육 내용
- Abdurahman et al. (2024, S15): LLM의 WEIRD bias (142% 증가된 동의 확률), 재현성 위기
- **시사점**: AI 거버넌스 태스크포스는 심리학 고유의 윤리 이슈(WEIRD bias, 참가자 대체 불가, 임상 고위험)를 중심으로 정책 수립. 한국 대학원생의 안전성·책임성·투명성 요구를 반영한 교육 설계

---

### B2.2 데이터 사이언스 (22편)

#### 발견 5: 심리학 특화 데이터 사이언스 교과과정은 글로벌 확산 추세이며, R/tidyverse 기반이 표준으로 자리잡고 있다

- **근거 강도: 중** (교과과정 사례 5편, 교재 3편, 서지분석 1편)
- Neth (P2-B2-011): Konstanz 대학 — ds4psy R 패키지 기반 심리학 데이터 사이언스 교재
- Garrison (P3-S020): Wake Forest — DataScience4Psych R/tidyverse 교재 및 강좌
- Ben-Gurion (P2-B2-012): 심리학 NLP 특화 데이터 사이언스 교과
- Penn LPS (P1-B2-022): 데이터 분석-심리학 통합 학부 학위 프로그램
- UT Austin (P3-S021): Behavioral Data Science Initiative
- P1-B2-008: 1,245건 서지분석 — 데이터 시각화·텍스트 마이닝·AI 등 분야 간 융합 증가
- **시사점**: N3 심리데이터 분석I은 R/tidyverse를 기본 도구로 채택하고, ds4psy/DataScience4Psych 모델을 참조하여 심리학 데이터셋 중심 교과 설계

#### 발견 6: ML/NLP 기법은 심리학 연구 전 분야에서 급속히 확산되며, 학부 수준 교육의 필요성이 증대되고 있다

- **근거 강도: 강** (Annual Review 2편, Nature Reviews 1편, 체계적 리뷰 3편, 서지분석 1편)
- Cushman (2024, P1-B2-009): Annual Review of Psychology — 사회심리학 컴퓨터 모델링 체계적 리뷰
- P1-B2-011: Annual Review of Clinical Psychology — ML + 디지털 측정 심리 건강 평가
- P1-B2-013: Nature Reviews Psychology — NLP의 행동과학 텍스트 데이터 분석 종합 리뷰
- P1-B2-014: 1991-2023 심리학 NLP 4,909편 서지분석 — 2012년 이후 기하급수적 성장
- P3-S009: LLM 심리학 전 분야 응용 포괄적 리뷰 — 인지·행동, 임상·상담, 교육·발달, 사회·문화
- P3-S010: LLM 심리학적 텍스트 분류 — 최소 프로그래밍으로 구현 가능
- **시사점**: E1 심리통계학에 ML 기초 개념(지도학습, 비지도학습, 교차검증) 도입. N3에 NLP 기반 텍스트 분석 실습 모듈 추가

#### 발견 7: 오픈사이언스는 '신뢰성 혁명(credibility revolution)'으로 제도화되고 있으며, 교육 통합이 핵심이다

- **근거 강도: 강** (Science 논문 1편, Nature Reviews 1편, Royal Society 1편, 체계적 리뷰 2편, 실증 연구 2편)
- Nosek et al. (2015, S20): 100개 재현 연구 중 36%만 통계적 유의성 달성 — 재현성 위기의 규모 확립
- Korbmacher et al. (2023, S21): '위기'를 '혁명'으로 재프레이밍 — 구조적·절차적·공동체 3차원 긍정적 변화
- P3-S026: Nature Reviews Psychology — 사전등록, 등록 보고서, 프리프린트, 데이터/코드 공유의 진화
- P3-S025: Royal Society Open Science — 심리학 오픈 연구 국제 이니셔티브 매핑
- Pownall et al. (2023, P2-B2-016): 사전등록 집단이 오픈사이언스 이해도 유의미 향상
- Beaudry et al. (2024, P2-B2-017): 신입생 18%만 "재현성 위기" 인지, 그러나 오픈사이언스에 호의적
- P2-B2-025: 사전등록 연구가 방법론적 엄밀성·투명성에서 우위 확인
- **시사점**: '심리학 연구 입문' (1학년)에서 재현성 위기와 오픈사이언스를 필수 교육. 졸업논문 3트랙에 OSF 사전등록 의무화. 10주 연구 지도 프로그램에 Registered Reports 형식 도입

---

### B2.3 Python/R 실습 교육 (17편)

#### 발견 8: 심리학 전용 Python 교재와 교과과정이 확립되어 즉시 활용 가능하다

- **근거 강도: 중** (교재 2편, 교과과정 2편, 교수법 논문 2편)
- Dalmaijer et al. (2024, P1-B2-016): Python for Experimental Psychologists 2판 — PsychoPy/PyGaze 활용 실험 + Pandas/Statsmodels 분석
- Lund University (P1-B2-021): 행동과학 Python 프로그래밍 과정
- Frank et al. (2025, P3-S024): Experimentology — 오픈사이언스 접근 실험심리학 방법론 교재
- Mahner et al. (2025, P2-B2-015): 심리학·인지신경과학 코딩의 10대 원칙
- **시사점**: N2 과목의 Python 실습은 PsychoPy 라이브러리 기반 실험 설계 + Pandas 데이터 분석으로 구성. 코딩 10대 원칙(변경 추적, 코드 테스트, 코드 리뷰)을 학부 수준에서 교육

#### 발견 9: R 통계교육은 심리학과 전체 교과과정 전환의 성공 사례가 다수 존재한다

- **근거 강도: 중** (교과과정 사례 3편, 오픈 교재 2편, 실증 연구 1편)
- Glasgow PsyTeachR (P3-S023): 학부-대학원 전 수준 R 기반 재현 가능 연구 교육 전환 완료
- UMN (P1-B2-018): 학부 통계에 R 의무화 — 통계 태도와 오픈사이언스 태도 간 강한 상관
- Navarro (P1-B2-017): Learning Statistics with R — CC BY-SA 4.0, 전 세계 채택
- Cetinkaya-Rundel & Hardin (S19): IMS 2e — 시뮬레이션 기반 추론, 32개 대화형 튜토리얼
- **시사점**: E1 심리통계학을 R 기반으로 전환할 경우, Glasgow PsyTeachR 모델(Level 1-3 체계적 경로)을 참조. Navarro 교재의 CC 라이선스를 활용하여 한국어 번역/심리학 데이터 적용 가능

#### 발견 10: 비전공자 대상 코딩 교육은 인터랙티브 OER과 증거 기반 교수법이 효과적이다

- **근거 강도: 중** (실증 연구 2편, OER 개발 1편, 체계적 리뷰 1편)
- P1-B2-019: learnr/Shiny 기반 인터랙티브 OER — 사회과학 학부생의 제한적 수학/통계 배경 고려
- P1-B2-020: Washington 대학 증거 기반 Python 교수법 — 플립드 구조, 다중 표현(multiple representations)
- P2-B2-018: 62개 실증 연구 종합 — 교직원 역량 개발과 기관 리더십이 핵심 동인
- Bainbridge (P1-B2-012): 빅데이터 심리학 교재 — 컴퓨터 훈련 없는 학부생 대상 설계
- **시사점**: N2/N3의 코딩 실습은 learnr/Shiny 기반 인터랙티브 환경에서 시작하여 점진적으로 독립 코딩으로 전환. 플립드 구조와 다중 표현 교수법 적용

---

### B2.4 연구 파이프라인 AI 통합 (23편)

#### 발견 11: AI 기반 체계적 문헌검색 자동화는 스크리닝 부담을 60% 이상 감소시키면서 90% 이상 재현율을 유지한다

- **근거 강도: 강** (체계적 리뷰 2편, 진단 정확도 연구 1편, 도구 비교 2편)
- P1-B2-023: NLP/ML/DL 활용 SLR 자동화 포괄적 리뷰 — 수동 스크리닝 60%+ 감소, 재현율 90%+ 유지
- Krag et al. (P1-B2-024): 6개 LLM 초록 스크리닝 진단 정확도 비교 — GPT-4o가 95% 이상 정확도
- P2-B2-020: ACM 게재 — Review Copilot, LLMSurver 등 최신 도구 비교
- P2-B2-021: AutoLit Review — Human-in-the-Loop AI 시스템
- P2-B2-024: SPARK — 수집·조직·필터링·스캐폴딩 자동화
- **시사점**: 학부생 연구 캡스톤에서 AI 보조 문헌검색을 표준 워크플로로 도입. 단, Human-in-the-Loop 원칙 필수 교육

#### 발견 12: 모바일 ESM/디지털 표현형은 심리학 데이터 수집 패러다임을 변혁하고 있다

- **근거 강도: 중** (체계적 리뷰 3편, 서지분석 1편, RCT 1편)
- P1-B2-025: ESM-Quest 앱 — 일상생활 실시간 데이터 수집
- P1-B2-026: 모바일 EMA/EMI 2,222건 서지분석 — 지속적 정확성/효율성 향상
- P1-B2-015: 디지털 표현형 74편 체계적 리뷰 — 2023년 출판 급증
- P3-S016: 42편 스코핑 리뷰 — 웨어러블/스마트폰 패시브 센싱 + ML 정신건강 모니터링
- P3-S018: 디지털 표현형 기반 개인화 웰빙 중재 RCT
- **시사점**: N3에 ESM/디지털 표현형 데이터 수집·분석 실습 모듈 추가. E10 뇌이미징 DS와 연계하여 다중모달 데이터 파이프라인 교육

#### 발견 13: AI 보조 논문작성은 구조화·편집 단계에서 효과적이나, 비판적 분석·독창성에 한계가 있다

- **근거 강도: 중** (체계적 리뷰 2편, 실증 연구 2편, 정책 분석 1편)
- P3-S004: 2023-2025 근거 종합 — GenAI 피드백이 학술 글쓰기 품질 향상 + 수정 동기 증진
- P3-S005: 박사과정 학생 실증 — 아이디어 생성, 구조화, 문헌 합성, 편집 등 6대 영역에서 활용
- P1-B2-029: RAG+LLM 에이전트 리뷰 자동화 — 최상위 저널 기준에는 미달
- P1-B2-007: ICMJE 2023 — 생성형 AI는 저자 기준 충족 불가
- P3-S013: 학생 절반이 GenAI 과제 사용이 윤리적이라 인식 — 처벌보다 교육 강조 필요
- **시사점**: 졸업논문 3트랙에서 AI 보조 글쓰기의 허용 범위와 공개 요건을 명확히 규정. 구조화·편집 보조는 허용하되, AI 생성 내용의 출처 표시 의무화

#### 발견 14: 자동화 데이터 파이프라인은 행동 연구의 효율성과 재현성을 동시에 향상시킨다

- **근거 강도: 중** (도구 개발 2편, 체계적 리뷰 1편, 실증 연구 1편)
- P3-S027: Nature 게재 — 행동 표현형 자동화 파이프라인 — 오류 감소, 시간 절약, 공유 향상
- P1-B2-027: 데이터 시각화 + AI 의사결정 127편 리뷰 — AI가 수동 탐지 불가능 패턴 발견
- P3-S019: Duke 인지과학 시각화 프로젝트
- P2-B2-022: NLP 기반 인터넷 CBT 치료 결과 예측
- **시사점**: 학부생 연구에서 데이터 수집-전처리-분석-시각화 전 과정을 코드 기반으로 문서화하는 재현 가능 파이프라인 교육

---

## 근거 강도 요약표

| 발견 | 근거 강도 | 메타분석/RCT | 체계적 리뷰 | 사례/준실험 | 전문가의견 |
|------|----------|-------------|-----------|-----------|-----------|
| 1. GenAI 교육 효과 (안내된 사용) | **강** | 4+2 | 1 | — | — |
| 2. AI 튜터링 효과 | **강** | 2+2 | 1 | — | — |
| 3. AI 리터러시 다차원 역량 | **중** | — | 3 | 3 | 1 |
| 4. AI 윤리 교육 내재화 | **중** | — | 4 | 2 | 2 |
| 5. DS 교과과정 글로벌 확산 | **중** | — | 1 | 5 | 3 |
| 6. ML/NLP 확산 | **강** | — | 6 | 1 | — |
| 7. 오픈사이언스 제도화 | **강** | 1 | 4 | 2 | — |
| 8. Python 심리학 교재 확립 | **중** | — | — | 4 | 2 |
| 9. R 교과과정 전환 성공 | **중** | — | — | 4 | 2 |
| 10. 비전공자 코딩 교수법 | **중** | — | 1 | 3 | — |
| 11. 문헌검색 AI 자동화 | **강** | — | 3 | 2 | — |
| 12. ESM/디지털 표현형 | **중** | 1 | 3 | 1 | — |
| 13. AI 보조 논문작성 | **중** | — | 2 | 2 | 1 |
| 14. 자동화 데이터 파이프라인 | **중** | — | 1 | 3 | — |

---

## 교과과정 시사점

### N2 심리과학을 위한 인공지능 (2학년, 3학점)

| 근거 기반 권고 | 핵심 소스 | 근거 강도 |
|---------------|----------|----------|
| GenAI 활용 시 구조화된 프롬프트 가이드라인과 scaffolding 필수 설계 | P3-S007, S008, S006, S035 | 강 |
| AI 리터러시를 정의적·행동적·인지적·윤리적 4차원으로 교육 | P2-B2-002, P1-B2-004 | 중 |
| LLM의 한계(WEIRD bias, 재현성, zero-shot 한계) 실증적 교육 | S15 | 강 |
| 행동과학 개입 설계에 LLM 활용 — 3단계 사용자 모델(설계자-중개자-수혜자) | S13 | 중 |
| GitHub 코딩 튜토리얼 기반 LLM 심리 평가 실습 | S14 | 강 |
| AI 윤리를 독립 주제가 아닌 매 실습에 내재화 | P3-S012, P2-B2-004 | 중 |
| PsychoPy + Python 기반 실험 설계 실습 | P1-B2-016 | 중 |

### N3 심리데이터 분석I (2학년, 3학점)

| 근거 기반 권고 | 핵심 소스 | 근거 강도 |
|---------------|----------|----------|
| R/tidyverse를 기본 분석 도구로 채택 | P2-B2-011, P3-S020, S19 | 중 |
| 시뮬레이션 기반 추론(randomization, bootstrapping) 우선 교육 | S19 | 중 |
| 심리학 데이터셋 기반 인터랙티브 튜토리얼(learnr/Shiny) 개발 | P1-B2-019, S19 | 중 |
| NLP 기반 텍스트 분석 입문 모듈 추가 | P1-B2-013, P1-B2-014 | 강 |
| ESM/디지털 표현형 데이터 분석 실습 | P1-B2-025, P3-S016 | 중 |
| 재현 가능 워크플로(R Markdown/Quarto) 필수 | P2-B2-015, P3-S024 | 중 |

### E1 심리통계학

| 근거 기반 권고 | 핵심 소스 | 근거 강도 |
|---------------|----------|----------|
| R 기반 교육 전환 — Glasgow PsyTeachR 모델 참조 | P3-S023, P1-B2-017, P1-B2-018 | 중 |
| ML 기초 개념(지도학습, 교차검증) 소개 | P1-B2-009, P1-B2-010 | 강 |
| 재현성 위기와 통계적 검정력의 관계 교육 | S20, S21 | 강 |
| 오픈사이언스 실천(사전등록, 효과크기 보고) 통합 | P2-B2-016, P2-B2-025 | 중 |

### E10 뇌이미징 데이터 사이언스

| 근거 기반 권고 | 핵심 소스 | 근거 강도 |
|---------------|----------|----------|
| 딥러닝 인지과학 모델의 이론적 기초 교육 | P2-B2-009, P2-B2-010 | 중 |
| 자동화 데이터 파이프라인 설계 원칙 교육 | P3-S027, P2-B2-015 | 중 |
| 웨어러블/센서 데이터 + ML 분석 통합 | P3-S016, P3-S017 | 중 |

---

## 교차 분기 연계

### B1 (교과과정 설계) 연계

| B2 발견 | B1 연계점 | 시사점 |
|---------|----------|--------|
| GenAI 안내된 사용 효과 (발견 1) | PBL 교수법 | PBL 과제에 구조화된 AI 활용 가이드라인 통합 |
| 오픈사이언스 제도화 (발견 7) | 교과과정 개편 동기 | 재현성 혁명을 BMBM 모듈 설계의 핵심 원칙으로 |
| DS 교과과정 글로벌 확산 (발견 5) | 벤치마킹 | Penn LPS, UT Austin 모델 참조한 교과 설계 |

### B3 (교수법 혁신) 연계

| B2 발견 | B3 연계점 | 시사점 |
|---------|----------|--------|
| AI 튜터링 효과 (발견 2) | 수업방법 혁신 | ITS 도입이 PBL 비중 확대(13%→50%)의 보조 수단 |
| 비전공자 코딩 교수법 (발견 10) | 능동적 학습 | 플립드 구조 + 인터랙티브 OER = 코딩 수업 표준 모델 |
| 안내된 GenAI 사용 (발견 1) | Brain-Mind-Behavior Studio | 스튜디오 수업에 ChatGPT scaffolding 통합 |

### B5 (교수역량 개발) 연계

| B2 발견 | B5 연계점 | 시사점 |
|---------|----------|--------|
| AI 리터러시 다차원 (발견 3) | AI Teaching Bootcamp | 교수진 AI 리터러시 4차원 역량 개발 |
| R 교과과정 전환 (발견 9) | 교수혁신팟 | Glasgow 모델 기반 교수진 R 역량 개발 프로그램 |
| AI 윤리 내재화 (발견 4) | 교수진 연수 | 한국 맥락 AI 윤리 이슈(P3-S032, S033) 기반 연수 |

### B7 (평가 혁신) 연계

| B2 발견 | B7 연계점 | 시사점 |
|---------|----------|--------|
| AI 보조 논문작성 (발견 13) | 졸업논문 평가 | AI 활용 범위 규정 + 공개 요건 + 진정성 평가 기준 |
| 사전등록 교육 효과 (발견 7) | 연구 역량 평가 | OSF 사전등록을 졸업논문 필수 요건으로 |
| GenAI 학술 무결성 (발견 13) | 과제 평가 | AI 탐지보다 교육적 접근 — 과정 중심 평가 강화 |

---

## 잔여 지식 갭

### 갭 1: 심리학 특화 AI 리터러시 측정도구 부재

- 기존 AI 리터러시 척도(P2-B2-001에서 16개 리뷰)는 범용 또는 STEM 중심이며, 심리학 고유 역량(연구 윤리, 참가자 데이터, 임상 적용)을 포괄하지 않음
- **필요 연구**: 심리학 전공 학부생 대상 AI 리터러시 측정도구 개발 및 타당화

### 갭 2: 한국 심리학과의 R/Python 전환 사례 부재

- 글로벌 사례(Glasgow, UMN, Konstanz)는 풍부하나 한국 심리학과의 코딩 도구 전환 실증 연구 부재
- **필요 연구**: 서울대 심리학과 R/Python 전환 파일럿의 학생 학습 성과 및 태도 변화 추적 연구

### 갭 3: AI 튜터링의 심리학 교과 특화 효과 연구 부재

- ITS 메타분석(Ma 2014, P2-B2-003)은 STEM 교과 중심이며, 심리학 통계/방법론 수업에서의 AI 튜터 효과 실증 연구 부재
- **필요 연구**: N3 또는 E1에서 AI 튜터 도입 전후 학습 성과 비교 연구(준실험 설계)

### 갭 4: 디지털 표현형 데이터의 학부 수준 교육 모델 부재

- ESM/디지털 표현형은 연구 방법으로 확립되었으나, 학부 교과과정에서 이를 가르치는 체계적 교육 모델에 대한 연구 부재
- **필요 연구**: N3 또는 캡스톤에서 디지털 표현형 데이터 수집-분석 실습의 교수법 개발 및 평가

### 갭 5: AI 보조 연구의 장기적 학습 효과 연구 부재

- 현재 근거는 대부분 단기 실험(1학기 이내)이며, AI 도구 의존에 따른 장기적 연구 역량 발달에 대한 종단 연구 부재
- **필요 연구**: 1-2년 추적 연구 — AI 도구 사용 경험이 독립적 연구 수행 역량에 미치는 영향

---

## 참고문헌

### P0 소스 (10편)

1. Hecht, C. A., Ong, D. C., Clapper, M., et al. (2025). Using large language models in behavioral science interventions: Promise & risk. *Behavioral Science & Policy*, 11(1), 1-9. https://doi.org/10.1177/23794607251344698
2. Brickman, J., Gupta, M., & Oltmanns, J. R. (2025). Large language models for psychological assessment: A comprehensive overview. *Advances in Methods and Practices in Psychological Science*, 8. https://doi.org/10.1177/25152459251343582
3. Abdurahman, S., Atari, M., Karimi-Malekabadi, F., et al. (2024). Perils and opportunities in using large language models in psychological research. *PNAS Nexus*, 3(7), pgae245. https://doi.org/10.1093/pnasnexus/pgae245
4. Stade, E. C., Wiltsey Stirman, S., Ungar, L. H., et al. (2024). Large language models could change the future of behavioral healthcare. *npj Mental Health Research*, 3(1), Article 12. https://doi.org/10.1038/s44184-024-00056-z
5. APA (2024). Artificial intelligence and the field of psychology. *APA Policy Statement*. https://www.apa.org/about/policy/artificial-intelligence-psychology
6. APS Task Force (2023). Responsible AI for psychology: Ethics, transparency, and accountability. https://www.psychologicalscience.org/topics/artificial-intelligence
7. Cetinkaya-Rundel, M. & Hardin, J. (2023). *Introduction to Modern Statistics* (2nd ed.). OpenIntro. https://openintro-ims.netlify.app/ ; Related: (2022). An educator's perspective of the tidyverse. *Technology Innovations in Statistics Education*, 14(1). https://doi.org/10.5070/T514154352
8. Open Science Collaboration (2015). Estimating the reproducibility of psychological science. *Science*, 349(6251), aac4716. https://doi.org/10.1126/science.aac4716
9. Korbmacher, M., Azevedo, F., Pennington, C. R., et al. (2023). The replication crisis has led to positive structural, procedural, and community changes. *Communications Psychology*, 1(1), Article 3. https://doi.org/10.1038/s44271-023-00003-2
10. Center for Open Science (2013-ongoing). Preregistration & OSF training. https://www.cos.io/ ; https://osf.io/

### P1 소스 (30편)

11. 저자 복수 (2025). Generative AI in higher education psychology programs. *Australian Psychologist*. https://doi.org/10.1080/00050067.2025.2580236
12. 저자 복수 (2025). Teaching psychology in the era of digital intelligence. *Frontiers of Digital Education*. https://doi.org/10.1007/s44366-025-0043-1
13. 저자 복수 (2025). One year in the classroom with ChatGPT. *Frontiers in Education*, 10. https://doi.org/10.3389/feduc.2025.1574477
14. 저자 복수 (2025). Navigating the landscape of AI literacy education. *Humanities and Social Sciences Communications*. https://doi.org/10.1038/s41599-025-04583-8
15. 저자 복수 (2025). AI tutoring outperforms in-class active learning. *Scientific Reports*. https://doi.org/10.1038/s41598-025-97652-6
16. 저자 복수 (2024). Evaluating recent advances in affective intelligent tutoring systems. *Education Sciences*, 14(8), 839. https://doi.org/10.3390/educsci14080839
17. 저자 복수 (2024). Ethical use of AI for scientific writing. *PMC*. https://pmc.ncbi.nlm.nih.gov/articles/PMC11015711/
18. 저자 복수 (2025). Curriculum, pedagogy, and teaching/learning strategies in data science education. *Education Sciences*, 15(2), 186. https://doi.org/10.3390/educsci15020186
19. Cushman, F. (2024). Computational social psychology. *Annual Review of Psychology*, 75, 625-652. https://doi.org/10.1146/annurev-psych-021323-040420
20. 저자 복수 (2022). Applications of machine learning to behavioral sciences. *Discover Psychology*. https://doi.org/10.1007/s44202-022-00027-5
21. 저자 복수 (2023). Machine learning and the digital measurement of psychological health. *Annual Review of Clinical Psychology*. https://doi.org/10.1146/annurev-clinpsy-080921-073212
22. Bainbridge, W. A. (2024). *Big Data in the Psychological Sciences*. Cambridge University Press. ISBN 9781009343589.
23. 저자 복수 (2024). Using natural language processing to analyse text data in behavioural science. *Nature Reviews Psychology*. https://doi.org/10.1038/s44159-024-00392-z
24. 저자 복수 (2024). A bibliometric review of NLP applications in psychology. *Basic and Applied Social Psychology*, 47(2). https://doi.org/10.1080/01973533.2024.2433720
25. 저자 복수 (2025). Digital phenotyping for mental health. *Artificial Intelligence in Medicine*, 163. https://www.sciencedirect.com/science/article/abs/pii/S0933365725000296
26. Dalmaijer, E. S., Hirst, R. J., & Peirce, J. W. (2024). *Python for Experimental Psychologists* (2nd ed.). Routledge. https://doi.org/10.4324/9781315616933
27. Navarro, D. J. (2018). *Learning Statistics with R* (v0.6.1). Open Textbook. https://learningstatisticswithr.com/
28. University of Minnesota (2024). Teaching stats: R, open science, and AI. https://cla.umn.edu/psychology/news-events/story/teaching-stats-r-open-science-and-course-ai
29. 저자 복수 (2023). Teaching beginner-level computational social science. *Frontiers in Education*. https://doi.org/10.3389/feduc.2023.1130865
30. 저자 복수 (2024). Cracking the code: Python in undergraduate earth science. *Journal of Geoscience Education*. https://doi.org/10.1080/10899995.2024.2384338
31. Lund University (2023-2024). Programming for the behavioral sciences. https://www.humlab.lu.se/education/courses/programming-for-the-behavioral-sciences/
32. University of Pennsylvania (ongoing). Data analytics and psychology — bachelor's degree. https://lpsonline.sas.upenn.edu/academics/bachelors-degree/baas-concentrations/data-analytics-and-psychological-sciences
33. 저자 복수 (2024). Towards the automation of systematic reviews. *Artificial Intelligence Review*. https://doi.org/10.1007/s10462-024-10844-w
34. Krag, C. H. et al. (2024). LLMs for abstract screening in systematic reviews. *medRxiv*. https://www.medrxiv.org/content/10.1101/2024.10.01.24314702v1
35. 저자 복수 (2024). ESM-Quest: Mobile assessment. *Frontiers in Psychology*. https://doi.org/10.3389/fpsyg.2023.1271422
36. 저자 복수 (2024). Mobile-based ecological momentary assessment. *Frontiers in Psychiatry*. https://doi.org/10.3389/fpsyt.2024.1300739
37. 저자 복수 (2025). Data visualization in AI-assisted decision-making. *Frontiers in Communication*. https://doi.org/10.3389/fcomm.2025.1605655
38. 저자 복수 (2026). Current developments of psychological research and the use of AI. *Psychological Research*. https://doi.org/10.1007/s00426-026-02246-0
39. 저자 복수 (2025). AI-assisted tools for scientific review writing. *ACS Applied Materials & Interfaces*. https://doi.org/10.1021/acsami.5c08837
40. 저자 복수 (2024). AI, academic publishing, scientific writing, peer review, and ethics. *PMC*. https://pmc.ncbi.nlm.nih.gov/articles/PMC11259451/

### P2 소스 (25편)

41. Lintner, T. (2024). A systematic review of AI literacy scales. *npj Science of Learning*. https://doi.org/10.1038/s41539-024-00264-4
42. Ng, D. T. K., Wu, W., Leung, J. K. L., et al. (2024). Design and validation of the AI literacy questionnaire. *British Journal of Educational Technology*. https://doi.org/10.1111/bjet.13411
43. 저자 복수 (2025). Effects of intelligent tutoring systems on educational outcomes. *International Journal of Distance Education Technologies*. https://doi.org/10.4018/IJDET.363420
44. Zhu, H., Sun, Y., & Yang, J. (2025). Towards responsible AI in education. *Humanities and Social Sciences Communications*. https://doi.org/10.1057/s41599-025-05252-6
45. 저자 복수 (2024). Unpacking the role of AI ethics online education. *International Journal of STEM Education*. https://doi.org/10.1186/s40594-024-00493-4
46. 저자 복수 (2025). Higher education students' perceptions of ChatGPT. *PMC*. https://pmc.ncbi.nlm.nih.gov/articles/PMC11798494/
47. Baker, R. S. & Hawn, A. (2022). Algorithmic bias in education. *International Journal of AI in Education*. https://doi.org/10.1007/s40593-021-00285-9
48. Hou, Y. & Huang, J. (2025). NLP for social science research. *Chinese Journal of Sociology*. https://doi.org/10.1177/2057150X241306780
49. Milliere, R. (2024). Philosophy of cognitive science in the age of deep learning. *WIREs Cognitive Science*. https://doi.org/10.1002/wcs.1684
50. Nature Editors (2024). Deep learning models in cognitive sciences (collection). https://www.nature.com/collections/dbcdgiagfj
51. Neth, H. (2024). *Data Science for Psychologists (ds4psy)* (v1.2.0). https://bookdown.org/hneth/ds4psy/
52. Ben-Gurion University (2024). Data science for psychology: Natural language. https://ds4psych.com/
53. 저자 복수 (2023). Digital transformation and digital literacy in higher education. *Humanities and Social Sciences Communications*. https://doi.org/10.1057/s41599-023-01875-9
54. 이각명, 권상희 (2025). 사회과학 분야의 인공지능 연구논문 동향 분석. *한국IT서비스학회지*. https://koreascience.kr/article/JAKO202520639605243.pdf
55. Mahner, F. P., Roth, J., Duan, Y., et al. (2025). Ten principles for reliable coding in psychology. *Communications Psychology*. https://doi.org/10.1038/s44271-025-00236-3
56. Pownall, M., Pennington, C. R., Norris, E., et al. (2023). Evaluating study preregistration in undergraduate dissertation. *AMPPS*. https://doi.org/10.1177/25152459231202724
57. Beaudry, J. L., Williams, M. N., Philipp, M. C., & Kothe, E. J. (2024). What do incoming students believe about open science? *Teaching of Psychology*. https://doi.org/10.1177/00986283221100276
58. 저자 복수 (2026). Advancing digital literacy in higher education. *Discover Education*. https://doi.org/10.1007/s44217-026-01256-9
59. 저자 (2025). 언어 및 언어교육 전공 대학생들의 AI 리터러시 연구. *한국콘텐츠학회논문지*. https://www.dbpia.co.kr/journal/articleDetail?nodeId=NODE11202617
60. 저자 복수 (2025). AI tools for automating systematic literature reviews. *ACM ICSECA*. https://doi.org/10.1145/3747912.3747962
61. 저자 복수 (2025). Human-in-the-loop AI system for systematic literature review (AutoLit). *PMC*. https://pmc.ncbi.nlm.nih.gov/articles/PMC12552804/
62. 저자 복수 (2025). NLP models for predicting treatment outcomes in internet-delivered CBT. *Internet Interventions*. https://doi.org/10.1016/j.invent.2025.100806
63. 저자 복수 (2025). Accepted with minor revisions: Value of AI-assisted scientific writing. *arXiv*. https://arxiv.org/abs/2511.12529
64. 저자 복수 (2024). SPARK: Systematic processing and automated review kit. *MethodsX*. https://doi.org/10.1016/j.mex.2024.103082
65. 저자 복수 (2024). Preregistration in practice. *Behavior Research Methods*. https://doi.org/10.3758/s13428-023-02277-0

### P3 소스 (35편)

66. Kestin, G., Miller, K., McCarty, L. S., et al. (2025). AI tutoring outperforms active learning (Harvard RCT). *Scientific Reports*, 15, 17458. https://doi.org/10.1038/s41598-025-97652-6
67. 저자 복수 (2025). A systematic review of AI-driven ITS in K-12 education. *npj Science of Learning*, 10, 53. https://doi.org/10.1038/s41539-025-00320-7
68. Ma, W., Adesope, O. O., Nesbit, J. C., & Liu, Q. (2014). Intelligent tutoring systems and learning outcomes: A meta-analysis. *Journal of Educational Psychology*, 106(4), 901-918. https://doi.org/10.1037/a0037123
69. 저자 복수 (2025). The impact of generative AI on academic reading and writing. *Frontiers in Education*, 10. https://doi.org/10.3389/feduc.2025.1711718
70. 저자 복수 (2025). Exploring PhD students' utilization of GenAI in academic writing. *Journal of English for Academic Purposes*. https://www.sciencedirect.com/science/article/pii/S1475158525001432
71. 저자 복수 (2024). Does ChatGPT enhance student learning? *Computers & Education*. https://www.sciencedirect.com/science/article/pii/S0360131524002380
72. Ma, S. et al. (2025). A meta-analysis of the impact of GenAI on learning outcomes. *Journal of Computer Assisted Learning*. https://doi.org/10.1111/jcal.70117
73. 저자 복수 (2025). Undergraduate students' learning outcomes with ChatGPT. *Computers & Education: AI*. https://www.sciencedirect.com/science/article/pii/S2666920X25001766
74. 저자 복수 (2025). Exploring the frontiers of LLMs in psychological applications. *Artificial Intelligence Review*, 58, 157. https://doi.org/10.1007/s10462-025-11297-5
75. 저자 복수 (2025). Validating LLMs for psychological text classification. *Frontiers in Social Psychology*. https://doi.org/10.3389/frsps.2025.1460277
76. 저자 복수 (2025). A systematic review of how educators integrate ethics into AI curriculum. *Journal of Research on Technology in Education*. https://doi.org/10.1080/15391523.2025.2551112
77. 저자 복수 (2025). AI ethics education: A systematic literature review. *Computers & Education: AI*. https://www.sciencedirect.com/science/article/pii/S2666920X25000451
78. 저자 복수 (2025). Reassessing academic integrity in the age of AI. *International Journal of Information Management*. https://www.sciencedirect.com/science/article/pii/S2590291125000269
79. 저자 복수 (2025). The AI literacy heptagon. *arXiv*. https://arxiv.org/html/2509.18900v1
80. OECD & European Commission (2025-2026). AI literacy framework. https://oecdedutoday.com/new-ai-literacy-framework-to-equip-youth-in-an-age-of-ai/
81. 저자 복수 (2025). Passive sensing for mental health monitoring. *JMIR*, 27(1), e77066. https://www.jmir.org/2025/1/e77066
82. 저자 복수 (2025). Fusing wearable biosensors with AI for mental health monitoring. *Sensors* / PMC. https://pmc.ncbi.nlm.nih.gov/articles/PMC12025234/
83. 저자 복수 (2024). Optimizing personalized psychological well-being interventions through digital phenotyping. *Frontiers in Psychology*. https://doi.org/10.3389/fpsyg.2024.1479269
84. Duke University Bass Connections (2024-2025). Improving data visualization with cognitive science. https://bassconnections.duke.edu/project/improving-data-visualization-cognitive-science-2024-2025/
85. Garrison, S. M. (2024-2025). Data Science for Psychologists (DataScience4Psych). Wake Forest University. https://datascience4psych.github.io/DataScience4Psych/
86. University of Texas at Austin (2024). Behavioral Data Science Initiative. https://liberalarts.utexas.edu/psychology/undergraduate-program/behavioral-data-science-initiative/index.html
87. 저자 복수 (2025). Survey of NLP for education. *arXiv*. https://arxiv.org/abs/2401.07518
88. University of Glasgow PsyTeachR Team (2024). Reproducible research in R for psychology. https://psyteachr.github.io/
89. Frank, M. C. et al. (2025). *Experimentology: An open science approach to experimental psychology methods*. MIT Press. https://experimentology.io/
90. 저자 복수 (2025). International initiatives to enhance open research in psychology. *Royal Society Open Science*. https://doi.org/10.1098/rsos.241726
91. 저자 복수 (2025). Evolving perspectives on open science. *Nature Reviews Psychology*. https://doi.org/10.1038/s44159-025-00487-1
92. 저자 복수 (2025). Automated pipeline for operant behavior phenotyping. *NPP — Digital Psychiatry and Neuroscience*. https://doi.org/10.1038/s44277-025-00046-9
93. Google DeepMind LearnLM Team (2025). LearnLM: AI tutoring can safely and effectively support learning. https://storage.googleapis.com/deepmind-media/LearnLM/learnLM_nov25.pdf
94. 저자 복수 (2025). LLMs in education: A systematic review. *Computers & Education: AI*. https://www.sciencedirect.com/science/article/pii/S2666920X25001699
95. UNESCO (2024). AI competency frameworks for students and teachers. https://www.unesco.org/en/articles/ai-and-futures-education
96. 저자 복수 (2025). A systematic review of AI's early impact on higher education. *Frontiers in Education*, 10. https://doi.org/10.3389/feduc.2025.1522841
97. 저자 복수 (2025). 인공지능 윤리교육의 현황과 과제. KCI 등재 학술지. https://www.kci.go.kr/kciportal/ci/sereArticleSearch/ciSereArtiView.kci?sereArticleSearchBean.artiId=ART003197677
98. 저자 복수 (2024). 대학원생의 인공지능 윤리교육에 대한 교육 요구 분석. KCI 등재 학술지. https://www.kci.go.kr/kciportal/ci/sereArticleSearch/ciSereArtiView.kci?sereArticleSearchBean.artiId=ART003064744
99. 저자 복수 (2024). 대학 AI 활용 교육 연구동향. KCI 등재 학술지. https://www.kci.go.kr/kciportal/ci/sereArticleSearch/ciSereArtiView.kci?sereArticleSearchBean.artiId=ART003166412
100. 저자 복수 (2025). Does GenAI improve students' higher-order thinking? *PMC*. https://pmc.ncbi.nlm.nih.gov/articles/PMC12734368/

---

*종합 완료: 2026-03-13 | 수행자: Claude Opus 4.6 | 상태: B2 근거 종합 완료*
