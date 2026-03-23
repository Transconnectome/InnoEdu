# P3 갭필·심화 검색 재개 프롬프트

> 아래 프롬프트를 새 세션에서 그대로 붙여넣으면 P3가 시작됩니다.

---

## 재개 프롬프트 (복사하여 사용)

```
P0(60편) + P1(205편) + P2(165편) = 430편이 완료되었다. 이제 P3: 170편 갭필·심화 검색을 실행한다.

## 컨텍스트
- P0+P1+P2 통합 보고서: `research/progress_report_P0P1P2.md` 읽기
- P2 결과: `research/data_charting/P2/B{1-7}_sources.md` 7개 파일 읽기
- P1 결과 (중복 방지용): `research/data_charting/P1/B{1-7}_sources.md` 7개 파일 읽기
- Knowledge Tree: `research/knowledge_tree.md` 읽기
- P0 소스 (중복 방지용): `research/preliminary_sources_60.md`
- P0 차팅 (중복 방지용): `research/data_charting/P0/B{1-7}_charting.md`

## P3 목표
7개 분기별 병렬 에이전트로 총 170편 신규 소스 검색 + 간략 데이터 차팅.
리프 갭필 + Citation Chaining + 최신문헌 확보.

## P3 분기별 목표

| Agent | 분기 | 목표 편수 | 산출 파일 | 보강 전략 |
|-------|------|----------|----------|---------|
| P3-B1 | BMBM 교과과정 | 29편 | research/data_charting/P3/B1_sources.md | B1.5.2(+3), B1.1.4(+2), B1.4.3(+2), B1.5.1(+2), B1.5.3(+2) |
| P3-B2 | AI·데이터 방법론 | 35편 | research/data_charting/P3/B2_sources.md | B2.1.3(+2), B2.4.4(+2), B2.2.1(+2), B2.3.1(+1), B2.4.2(+1) |
| P3-B3 | PBL 수업혁신 | 26편 | research/data_charting/P3/B3_sources.md | B3.1.4(+2), B3.4.2(+2), B3.3.2(+1), B3.4.3(+1) |
| P3-B4 | 학부생 연구 | 27편 | research/data_charting/P3/B4_sources.md | B4.3 IRB/데이터보호(+5), B4.4 학술투고(+5) |
| P3-B5 | 교수역량 강화 | 18편 | research/data_charting/P3/B5_sources.md | B5.3.2(+2), B5.3.3(+2), SoTL 실증 |
| P3-B6 | 글로벌 벤치마크 | 21편 | research/data_charting/P3/B6_sources.md | B6.3.3 아시아 AI(+3), B6.4 정책(+5) |
| P3-B7 | 측정·평가 | 14편 | research/data_charting/P3/B7_sources.md | B7.4 AI 정책·무결성(+5) |

## P3 핵심 차별점: 5대 검색 전략

### 전략 1: 리프 갭필 (~50편)
누적 <5편인 리프 카테고리를 우선 보강. 구체적 목록:

**최우선 (≤2편)**:
- B1.5.2 실험설계 측정 개편 (2편) → +3편

**우선 (3편)**:
- B1.1.4 심리학 표준 교과과정 → +2편
- B1.4.3 조직 경제 빅데이터 → +2편
- B1.5.1 심리통계 혁신 → +2편
- B1.5.3 데이터분석 도구 교육 → +2편
- B2.1.3 AI 튜터링 시스템 → +2편
- B2.2.1 데이터분석 교과 설계 → +2편
- B2.4.4 논문작성 AI 보조 → +2편
- B3.1.4 PBL 평가 방법 → +2편
- B3.4.2 Reflective Studio → +2편

**보통 (4편)**: 나머지 ~22개 리프 → 각 +1편

### 전략 2: Forward Citation (~40편)
P0+P1+P2 Tier 1 핵심 논문(피인용 상위)의 후속 연구 추적.

**핵심 시드 논문**:
- Freeman et al. (2014) Active learning meta-analysis → 후속 메타분석
- Theobald et al. (2020) Active learning equity → 후속 실증
- APA Guidelines 3.0 → 적용 사례 연구
- Nosek et al. (2015) Replication → 후속 오픈사이언스 연구

### 전략 3: Backward Citation (~30편)
핵심 리뷰/메타분석의 참고문헌에서 누락된 원전 확보.

### 전략 4: 2025-2026 최신 (~30편)
AI 교육, 심리학 교육 최신 출판물 집중 검색.

**키워드**:
- "AI in psychology education 2025-2026"
- "generative AI higher education 2025"
- "psychology curriculum reform 2025"
- "undergraduate research AI 2025"

### 전략 5: Grey Literature 보충 (~20편)
기관 정책, CTL 보고서, 프로그램 평가 문서.

**한국어 검색 (KCI/RISS 지속)**:
- "심리학 교과과정 개편" 2024-2026
- "대학 AI 교육 정책" 2024-2026
- "교수학습센터 성과 보고" 2024-2026

## 한국어 소스 목표
- P2에서 36편 달성. P3에서 **추가 15-20편** 목표.
- 누적 한국어 소스 목표: 50-55편

## 실행 순서
1. `mkdir -p research/data_charting/P3`
2. 위 입력 파일을 읽어 컨텍스트 파악 (특히 P2 B-sources 7개 파일로 기존 소스 목록 확인)
3. progress_report_P0P1P2.md에서 리프 갭 분석 확인
4. 7개 deep-research-agent를 동시에 백그라운드로 실행
5. 완료 후 통합 보고서 작성 → `research/data_charting/P3/progress_report_P3.md`

## 각 에이전트 프롬프트 구조
1. progress_report_P0P1P2.md에서 해당 분기 잔여 갭 확인
2. knowledge_tree.md에서 하위분기/리프 구조 읽기
3. P1 B{n}_sources.md + P2 B{n}_sources.md에서 기존 소스 확인 (중복 방지)
4. preliminary_sources_60.md에서 P0 소스 확인 (중복 방지)
5. 5대 전략에 따른 검색 실행:
   a. 리프 갭필: 미달 리프에 대해 WebSearch 2-3회
   b. Forward Citation: 핵심 시드 논문의 Google Scholar "Cited by" 검색
   c. Backward Citation: 핵심 리뷰의 참고문헌 검토
   d. 최신문헌: 2025-2026 출판물 집중 검색
   e. Grey Literature: 기관/정책 소스
6. PCC 기준 충족 소스 선별 (Tier 1 우선, 2020년 이후 우선)
7. 각 소스에 대해 간략 차팅: 제목, 저자, 연도, DOI/URL, 하위분기, Tier, 핵심 발견 2-3개
8. 마지막에 커버리지 요약: 하위분기별 발견 편수 + 갭 식별

## 리프 커버리지 검증 기준 (P3 최종)
- 97개 리프 카테고리 각각에 P0+P1+P2+P3 누적 최소 **3편 이상** (이상적: 5편)
- 29개 하위분기 각각에 P0+P1+P2+P3 누적 최소 **10편 이상**
- 미달 리프/하위분기는 P4 보고서에 명시적 식별

## 검증 기준
- 7개 분기 × 목표 편수 달성률 확인
- Tier 1 ≥ 50% 유지
- P0+P1+P2 430편과 중복 0편
- 한국어 소스 ≥ 15편 추가
- 누적 600편 달성
- 리프 커버리지: 97개 리프 중 ≥85개에 ≥5편
```

---

## P2 프롬프트 대비 변경 사항

| 항목 | P2 | P3 | 변경 사유 |
|------|-----|-----|----------|
| 컨텍스트 파일 | P0P1 보고서, P1 B-sources | **P0P1P2 보고서, P2 B-sources 추가** | 중복 방지 범위 확대 |
| 검색 전략 | DB 기반 키워드 검색 | **5대 전략 (갭필+Citation+최신+Grey)** | 잔여 갭 특화 |
| 리프 커버리지 기준 | 94개 리프 ≥80% (≥1편) | **97개 리프 ≥85개 (≥5편)** | 심화 커버리지 |
| 한국어 소스 목표 | 최소 25편 | **추가 15-20편 (누적 50-55편)** | 한국 맥락 심화 |
| 중복 방지 범위 | P0 60편 + P1 205편 | **P0 60편 + P1 205편 + P2 165편** | 누적 430편 전체 |
| 목표 편수 | 165편 | 170편 | 600편 - 430편 |
| Citation Chaining | 없음 | **Forward + Backward Citation** | P3 신규 전략 |

---

## P3 완료 후 다음 단계

### 즉시 실행
1. P0+P1+P2+P3 통합 보고서 → `research/progress_report_final.md`
2. NotebookLM 최종 소스 업데이트
3. 리프 커버리지 최종 점검 → PRISMA 데이터 준비
4. 메모리 업데이트

### P4 종합 (별도 세션)
1. Top 50 핵심 소스 선정
2. PRISMA-ScR 흐름도 최종 작성
3. 분기별 종합 보고서 (7개)
4. 과목별 Evidence Map (14개)
5. 최종 Scoping Review 보고서 → `research/final_report.md`
