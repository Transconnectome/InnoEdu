# P1 핵심문헌 검색 재개 프롬프트

> 아래 프롬프트를 새 세션에서 그대로 붙여넣으면 P1이 시작됩니다.

---

## 재개 프롬프트 (복사하여 사용)

```
P0 예비연구(60편 데이터 차팅 + Knowledge Tree 검증)가 완료되었다. 이제 P1: 200편 핵심문헌 검색을 실행한다.

## 컨텍스트
- P0 결과: `research/data_charting/P0/progress_report_P0.md` 읽기
- Knowledge Tree 검증: `research/data_charting/P0/tree_validation.md` 읽기
- 검색식: `research/search_prompts.md` 읽기
- Knowledge Tree: `research/knowledge_tree.md` 읽기
- 기존 60편: `research/preliminary_sources_60.md` (중복 방지용)

## P1 목표
7개 분기별 병렬 에이전트로 총 205편 신규 소스 검색 + 간략 데이터 차팅.
P0 갭 분석 결과를 반영한 분기별 목표:

| Agent | 분기 | 목표 편수 | 산출 파일 | 보강 우선 영역 |
|-------|------|----------|----------|--------------|
| P1-B1 | BMBM 교과과정 | 40편 | research/data_charting/P1/B1_sources.md | Mind/Behavior/Method 모듈 (0편→7편씩) |
| P1-B2 | AI·데이터 방법론 | 30편 | research/data_charting/P1/B2_sources.md | 데이터사이언스 교과, 연구파이프라인 AI |
| P1-B3 | PBL 수업혁신 | 30편 | research/data_charting/P1/B3_sources.md | 심리학 PBL, Flipped/TBL, AI 교수법 |
| P1-B4 | 학부생 연구 | 25편 | research/data_charting/P1/B4_sources.md | IRB 교육, 학술발표, 다중트랙 캡스톤 |
| P1-B5 | 교수역량 강화 | 25편 | research/data_charting/P1/B5_sources.md | 효과 연구, TIP 운영 사례, CTL 모델 |
| P1-B6 | 글로벌 벤치마크 | 25편 | research/data_charting/P1/B6_sources.md | Oxford/NUS 심화, 아시아 대학, 서울대 사례 |
| P1-B7 | 측정·평가 | 30편 | research/data_charting/P1/B7_sources.md | 프로그램 평가(8편), AI 정책(7편), 거버넌스(5편) |

## 실행 순서
1. `mkdir -p research/data_charting/P1`
2. 위 5개 입력 파일을 읽어 컨텍스트 파악
3. 7개 deep-research-agent를 동시에 백그라운드로 실행
4. 완료 후 통합 보고서 작성 → `research/data_charting/P1/progress_report_P1.md`

## 각 에이전트 프롬프트 구조
1. search_prompts.md에서 담당 분기 검색식 읽기
2. knowledge_tree.md에서 하위분기/리프 구조 읽기
3. preliminary_sources_60.md에서 기존 소스 확인 (중복 방지)
4. progress_report_P0.md에서 해당 분기 갭 확인
5. 하위분기별 WebSearch 3-5회 실행
6. PCC 기준 충족 소스 선별 (Tier 1 우선, 2020년 이후 우선)
7. 각 소스에 대해 간략 차팅: 제목, 저자, 연도, DOI/URL, 하위분기, Tier, 핵심 발견 2-3개
8. 마지막에 커버리지 요약: 하위분기별 발견 편수 + 갭 식별

## 검증 기준
- 7개 분기 × 목표 편수 달성률 확인
- Tier 1 ≥ 50% 유지
- P0 60편과 중복 없음
- 하위분기별 최소 2편 이상
```

---

## 추가 참고사항

### P1 완료 후 다음 단계
- **Wave 4 (통합)**: P0+P1 결과 통합 → `research/progress_report_P0P1.md`
- **P2 (확장조사)**: 200편 추가 — P1 갭 기반
- **P3 (갭필)**: 140편 — 리프 카테고리 최소 1편 보장
- **P4 (종합)**: Top 50 선정, PRISMA 흐름도, 최종 보고서

### NotebookLM 통합 (P1 완료 시)
- `InnoEdu_Literature_600` 노트북 생성
- P1 핵심 소스 50편 추가
- 분기별 종합 쿼리 실행

### 서지 재확인 필요 (P1에서 처리)
- S02: Dunn & McCarthy (2020) Teaching of Psychology — 정확한 제목 검색
- S04: Sejnowski & Churchland (2024) Annual Review of Neuroscience — 존재 확인
- S59: "CREWS" → Kaufman K-DOCS/CAT로 대체 확정 또는 원출처 확인
