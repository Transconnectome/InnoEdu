# P2 확장문헌 검색 재개 프롬프트

> 아래 프롬프트를 새 세션에서 그대로 붙여넣으면 P2가 시작됩니다.

---

## 재개 프롬프트 (복사하여 사용)

```
P0 예비연구(60편) + P1 핵심문헌(205편) = 265편이 완료되었다. 이제 P2: 165편 확장문헌 검색을 실행한다.

## 컨텍스트
- P0+P1 통합 보고서: `research/progress_report_P0P1.md` 읽기
- P1 결과 (중복 방지용): `research/data_charting/P1/B{1-7}_sources.md` 7개 파일 읽기
- Knowledge Tree: `research/knowledge_tree.md` 읽기
- 기존 60편: `research/preliminary_sources_60.md` (중복 방지용)
- P0 차팅: `research/data_charting/P0/B{1-7}_charting.md` (중복 방지용)

## P2 목표
7개 분기별 병렬 에이전트로 총 165편 신규 소스 검색 + 간략 데이터 차팅.
P0+P1 잔여 갭 분석 결과를 반영한 분기별 목표:

| Agent | 분기 | 목표 편수 | 산출 파일 | 보강 우선 영역 |
|-------|------|----------|----------|--------------|
| P2-B1 | BMBM 교과과정 | 30편 | research/data_charting/P2/B1_sources.md | 아시아 신경과학 사례, 한국 종단연구, 온라인 감각-지각 실습 |
| P2-B2 | AI·데이터 방법론 | 25편 | research/data_charting/P2/B2_sources.md | 리프별 최소 2편 보장, 심화 ML/NLP 응용 |
| P2-B3 | PBL 수업혁신 | 25편 | research/data_charting/P2/B3_sources.md | 한국 PBL (사회과학/심리학), 하위분야별 PBL |
| P2-B4 | 학부생 연구 | 20편 | research/data_charting/P2/B4_sources.md | URP 3년+ 종단, 심리학 특화 캡스톤 실증 |
| P2-B5 | 교수역량 강화 | 20편 | research/data_charting/P2/B5_sources.md | 한국 CTL, SoTL 실증, 월간 클리닉 사례 |
| P2-B6 | 글로벌 벤치마크 | 25편 | research/data_charting/P2/B6_sources.md | **서울대 사례, 한국 심리학 교육 (최우선)** |
| P2-B7 | 측정·평가 | 20편 | research/data_charting/P2/B7_sources.md | 리프별 최소 1편 보장, 한국 평가 도구 적응 |

## P2 핵심 차별점: 한국 맥락 집중 검색

### 한국어 검색 키워드 (KCI/RISS 활용)

| 영역 | 검색 키워드 | 목표 | 분기 | 데이터베이스 |
|------|-----------|------|------|------------|
| 한국 심리학 교육 | "심리학 교육" AND "교과과정" | 5-8편 | B6.3.2 | KCI, RISS |
| 한국 심리학 교육 | "한국심리학회" AND "교육" | 3-5편 | B6.3.2 | KCI |
| 서울대 교과 개편 | "서울대" AND "교과" OR "교육과정" | 3-5편 | B6.4.2 | RISS, 학내DB |
| 한국 PBL | "문제기반학습" AND "고등교육" | 3-5편 | B3.1.2 | KCI |
| 한국 PBL | "프로젝트학습" AND "대학" | 2-3편 | B3.1.2 | KCI |
| 한국 CTL | "교수학습센터" OR "교수학습지원" | 3-5편 | B5.4 | KCI, RISS |
| 한국 디지털전환 | "대학교육" AND "디지털전환" OR "AI교육" | 2-3편 | B5.1, B6.4 | KCI |
| 한국 학부 연구 | "학부생 연구" OR "학부연구프로그램" | 2-3편 | B4.1 | KCI, RISS |
| 한국 연구윤리 | "연구윤리" AND "대학" OR "IRB" | 2-3편 | B4.3 | KCI |

### 한국어 소스 목표
- 전체 P2 165편 중 **최소 25편** (15.2%)을 한국어 소스로 확보
- KCI/RISS 검색 우선, Google Scholar 한국어 검색 보조
- 한국심리학회지, 한국교육학연구, 교육공학연구 등 주요 학술지 타겟

## 실행 순서
1. `mkdir -p research/data_charting/P2`
2. 위 입력 파일을 읽어 컨텍스트 파악 (특히 P1 B-sources 7개 파일로 기존 소스 목록 확인)
3. 7개 deep-research-agent를 동시에 백그라운드로 실행
4. 완료 후 통합 보고서 작성 → `research/data_charting/P2/progress_report_P2.md`

## 각 에이전트 프롬프트 구조
1. progress_report_P0P1.md에서 해당 분기 잔여 갭 확인
2. knowledge_tree.md에서 하위분기/리프 구조 읽기
3. P1 B{n}_sources.md에서 기존 소스 확인 (중복 방지)
4. preliminary_sources_60.md에서 P0 소스 확인 (중복 방지)
5. 하위분기별 WebSearch 3-5회 실행
   - **영어 검색**: Google Scholar, Semantic Scholar, PubMed 우선
   - **한국어 검색**: KCI, RISS, 한국심리학회 DB 추가 (위 키워드 참조)
6. PCC 기준 충족 소스 선별 (Tier 1 우선, 2020년 이후 우선)
7. 각 소스에 대해 간략 차팅: 제목, 저자, 연도, DOI/URL, 하위분기, Tier, 핵심 발견 2-3개
8. 마지막에 커버리지 요약: 하위분기별 발견 편수 + 갭 식별

## 리프 커버리지 검증 기준 (P2 신규)
- 94개 리프 카테고리 각각에 P0+P1+P2 누적 최소 **1편 이상**
- 29개 하위분기 각각에 P0+P1+P2 누적 최소 **5편 이상**
- 미달 리프/하위분기는 P3 갭필 목표로 명시적 식별

## 검증 기준
- 7개 분기 × 목표 편수 달성률 확인
- Tier 1 ≥ 50% 유지
- P0 60편 + P1 205편과 중복 0편
- 한국어 소스 ≥ 25편 확인
- 리프 커버리지 ≥ 80% (94개 중 ≥ 75개)
```

---

## P1 프롬프트 대비 변경 사항

| 항목 | P1 | P2 | 변경 사유 |
|------|-----|-----|----------|
| 컨텍스트 파일 | P0 보고서, 검색식, KT | P0P1 통합 보고서, P1 B-sources 7개 | 중복 방지 강화 |
| 한국어 검색 | 없음 | **KCI/RISS 키워드 9개 영역** | 한국 맥락 최대 갭 |
| 리프 커버리지 검증 | 없음 | **94개 리프 ≥80% 기준** | P2 목표 |
| 한국어 소스 목표 | 없음 | **최소 25편 (15.2%)** | 사업계획서 한국 맥락 |
| 검색 DB | Google Scholar, Semantic Scholar | + **KCI, RISS, 한국심리학회** | 한국어 소스 확보 |
| 목표 편수 | 205편 (총) | 165편 (총) | P2 보강 전략 |
| 중복 방지 범위 | P0 60편 | **P0 60편 + P1 205편** | 누적 확대 |

---

## P2 완료 후 다음 단계

### 즉시 실행
1. P0+P1+P2 통합 보고서 → `research/progress_report_P0P1P2.md`
2. NotebookLM `InnoEdu_Literature_600` 소스 추가 (P2 핵심 30편)
3. 리프 커버리지 점검 → 미달 리프 목록 생성

### P3 갭필 (별도 세션)
1. 리프 커버리지 미달 카테고리 집중
2. ~170편 추가 → P0+P1+P2+P3 = 600편
3. PRISMA 흐름도 작성 준비

### P4 종합 (별도 세션)
1. Top 50 핵심 소스 선정
2. PRISMA-ScR 흐름도 최종 작성
3. 최종 종합 보고서 → `research/final_report.md`
