# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

**Inno-Edu 2031: 서울대 창의교육프로젝트** — 서울대학교 사회과학대학 심리학과의 교육 혁신 사업계획서 프로젝트.

- **사업책임자**: 차지욱 부교수 (심리학과)
- **사업기간**: 2년 (1차년도: 2026.3.1 ~ 2026.12.31)
- **1차년도 예산**: 70,000,000원
- **핵심 비전**: "AI 시대, 인간 이해의 중심으로서 심리학이 뇌-마음-행동(Brain-Mind-Behavior) 접근을 통합해 인간다움과 공존을 탐구하는 교육 혁신을 선도하기"

## Core Framework: Brain-Mind-Behavior-Method (BMBM)

심리학과 전공 39개 과목을 4대 모듈로 재편:

| 모듈 | 영역 | 과목 수 | 비중 |
|------|------|---------|------|
| Brain (뇌) | 인지신경과학 등 | 11개 | 28% |
| Mind (마음) | 인지·지각심리 등 | 8개 | 20.5% |
| Behavior (행동) | 사회·임상·발달심리 등 | 12개 | 31% |
| Method (방법) | 심리통계, AI, 데이터분석 등 | 8개 | 20.5% |

## Key Strategic Pillars

1. **교과과정 개편**: 14개 신설/개편 (41%) — 신설 4개 + 강화 개편 10개
2. **수업방법 혁신**: PBL 비중 확대 (13%→50%), Brain-Mind-Behavior Studio, AI 튜터 도입
3. **AI·데이터 기반 연구역량 체계 구축**: 학부생-교수 연구 매칭, 연구윤리·IRB 교육
4. **학부생 연구 역량 강화**: 졸업논문 3트랙, 10주 연구 지도 프로그램, 학술대회 지원

## New Courses (신설 4개)

1. 심리학 연구 입문 (1학년, 2학점) — Method 모듈
2. 심리과학을 위한 인공지능 (2학년, 3학점) — Method 모듈
3. 심리데이터 분석 I (2학년, 3학점) — Method 모듈
4. 학부생 연구 캡스톤 (4학년, 3학점) — Method 모듈

## Literature Review Status (문헌 조사 현황)

### 완료된 작업

| 단계 | 편수 | DOI 보유 | 상태 |
|------|------|---------|------|
| P0 예비연구 | 60편 | ~33개 | ✅ 완료 |
| P1 핵심문헌 | 205편 | ~111개 | ✅ 완료 |
| P2 확장문헌 | 165편 | ~94개 | ✅ 완료 |
| P3 갭필·심화 | 170편 | ~75개 | ✅ 완료 |
| **합계** | **600편** | **~328개** | ✅ |

### 품질 지표

- Tier 1 (peer-reviewed): 72.2% (433/600)
- 2020년 이후: ~87%
- 한국어 소스: 54편 (9.0%)
- 리프 커버리지: 97/97 (100%)
- 서지 감사: PASS (오류율 2.0%)

### Phase C/D 산출물 (전부 완료)

- 서지 품질 감사: `research/quality_audit/` (8 files)
- PRISMA 흐름도: `research/prisma_flow_diagram.md`
- Top 50 핵심 소스: `research/top50_core_sources.md`
- 분기별 종합: `research/synthesis/B{1-7}_synthesis.md` (7 files)
- 과목별 근거 매핑: `research/evidence_mapping/` (15 files)
- APA Goals 매핑: `research/apa_goals_mapping.md`
- 최종 보고서: `research/final_report.md`

## NotebookLM Notebooks

| 노트북 | ID | 소스 수 | 용도 |
|--------|-----|---------|------|
| InnoEdu_Literature_600 | `91cb74ba-cb54-4de1-98d6-26f5b9af1aa1` | 26개 | P0-P1 + Phase C/D 산출물 |
| innoedu_230 | `9a7c23bf-043a-472e-8111-eb13a39bbd20` | ~239 | DOI 기반 원문 논문 |

NLM CLI 명령어:
```bash
nlm notebook list                              # 노트북 목록
nlm notebook query <id> "질문"                   # 노트북에 질문
nlm source list <id>                            # 소스 목록
nlm source add <id> --url <url>                 # URL 소스 추가
nlm source add <id> --file <path>               # 파일 소스 추가
```

## Global Benchmarks

본 제안은 다음 글로벌 선도 모델을 참조하되 심리학 고유의 Brain-Mind-Behavior 통합 강점을 살린 차별화된 접근:
- Stanford AIMES, Harvard Bok Center, MIT DAILy, Oxford Summer Schools, NUS ChatGPT Study, Glasgow PsyTeachR

## APA Guidelines 3.0 연계

APA 5대 학습목표 + 4대 통합 주제(Cross-Cutting Integrative Themes)를 연구 파이프라인과 체계적으로 연계.

## Document Genre Rules (문서 작성 규칙)

이 프로젝트는 **기관 제안서(proposal)** 장르임. 반드시 다음을 준수:

- **기관 주어 사용**: "서울대학교 심리학과는", "본 학과는", "본 사업은"
- **구체적 수치 필수**: 백분율, 연도, 금액, 과목 수 등
- **객관적 어조**: 전문적, 근거 기반
- **절대 금지**: "나는", "내가", "저는" 등 개인 주어 / "생각한다", "믿는다" 등 주관적 표현

## File Naming Conventions (파일 네이밍 규칙)

### research/data_charting/
- `P{0-3}/B{1-7}_charting.md` — 분기별 차팅 (P0)
- `P{0-3}/B{1-7}_sources.md` — 분기별 소스 목록 (P1-P3)
- `P{0-3}/progress_report_P{n}.md` — 단계별 보고서

### research/synthesis/
- `B{1-7}_synthesis.md` — 분기별 종합 보고서

### research/evidence_mapping/
- `N{1-4}_evidence.md` — 신설 과목 근거 매핑
- `E{1-10}_evidence.md` — 강화 개편 과목 근거 매핑
- `mapping_summary.md` — 매핑 요약표

### research/quality_audit/
- `B{1-7}_audit.md` — 분기별 감사 결과
- `audit_summary.md` — 감사 종합 보고서

### plans/
- `curriculum_master_plan.md` — 교과과정 마스터플랜
- `governance_structure.md` — 거버넌스 구조
- `governance_charter.md` — 거버넌스 헌장
- `P{1-3}_resume_prompt.md` — 문헌검색 재개 프롬프트

## Branch Naming (B1-B7)

| 분기 | 영역 | 편수 |
|------|------|------|
| B1 | BMBM 교과과정 설계 | 110편 |
| B2 | AI·데이터 방법론 | 100편 |
| B3 | PBL 수업혁신 | 90편 |
| B4 | 학부생 연구역량 | 80편 |
| B5 | 교수역량 강화 | 70편 |
| B6 | 글로벌 벤치마크 | 80편 |
| B7 | 측정·평가·거버넌스 | 70편 |

## Implementation Timeline (1차년도)

| 시기 | 주요 내용 | 상태 |
|------|---------|------|
| 2026.03-04 | 교과운영위원회 논의, RA 채용 | ⚠️ 미착수 |
| 2026.04-05 | 신설 4과목 강의계획서 (서울대 양식) | ⚠️ 초안만 존재 |
| 2026.05-06 | 졸업논문 개선안 확정, 교수 배정 | 미착수 |
| 2026.06-07 | AI Teaching Bootcamp (교수진 12명) | 미착수 |
| 2026.08 | AI·데이터 분석 부트캠프 (학부생 20-30명) | 미착수 |
| 2026.09-12 | PBL 수업, 10주 연구지도 시범, 성과 평가 | 미착수 |
| 2026.12 | 교무처 교과과정 개편 승인, 2차년도 계획 | 미착수 |

## Current Blocking Issues (현재 블로킹 이슈)

1. **교과운영위원회 미소집** — 교수진 합의 없이 실행 불가
2. **RA/보조연구원 미채용** — 실행 인력 부재
3. **강의계획서 미공식화** — 마스터플랜 초안을 서울대 양식으로 전환 필요
4. **AI Teaching Bootcamp 미기획** — 6-7월 실시, 강사/장소/자료 미확보
5. **예산 집행 계획 미상세화** — 월별 집행 일정 없음

## Budget Structure

| 구분 | 금액 | 비중 |
|------|------|------|
| 인건비 | 10,500,000원 | 15% |
| 연구활동비 | 35,000,000원 | 50% |
| 연구수당 | 24,500,000원 | 35% |

## Research Team

- 연구책임자: 차지욱 (부교수)
- 참여 연구자 11명: 고성룡, 김가원, 김향숙, 석혜원, 안우영, 이수현, 이해연, 최인철, 최진영, Sowon Hahn (전원 심리학과 교수진)
- 보조연구원: 대학원생 2명 (미정)

## Governance

- **심리학혁신위원회(Psychology Innovation Council)**: 연 4회 — 교과 개편, AI 정책, 성과 평가
- **AI 거버넌스 태스크포스**: 학과장, 전산센터, 법무팀, 학생대표
- **교수혁신팟(Teaching Innovation Pods)**: 전임·초빙·겸임교원 12명 — 모듈별 교과 설계

## Useful Commands

```bash
# Git
git status && git diff                  # 변경 사항 확인
git log --oneline -10                   # 최근 커밋

# NotebookLM CLI
nlm notebook list                       # 전체 노트북 목록
nlm notebook query <id> "질문"           # 노트북에 질문
nlm source list <id>                    # 소스 목록
nlm source add <id> --url <doi_url>     # DOI URL 소스 추가

# DOI 추출 (research/ 전체)
grep -rhoP '10\.\d{4,9}/[^\s,;")\]>]+' research/ | sort -u

# 문헌 통계
grep -rc 'Tier 1' research/data_charting/   # Tier 1 카운트
wc -l research/data_charting/P*/B*          # 파일별 라인 수
```
