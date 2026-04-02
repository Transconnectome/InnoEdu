# S3 Prompt — 어떻게 진행되는가

## API Configuration
- model: gemini-3.1-flash-image-preview
- resolution: 4K (3840x2160 for 16:9)
- thinking_mode: high
- language: ko

## Rendering Rule
- Text with pt size + color → RENDER in image
- Fallback Layout / Self-Validation / Style Rules → DO NOT render, context only

## MASTER THEME
background: "#FFFFFF"
palette:
  primary: "#1A365D"
  accent: "#E69F00"
  secondary: "#0072B2"
  text: "#2D3748"

## Prompt for nanobanana2

Create a 16:9 horizontal Korean infographic on white background.

서울대학교 심리학과 1차년도 실행 일정.

**상단 제목** (28pt Bold #1A365D):
어떻게 진행되는가: 단계별 검증

**수평 타임라인** (중앙, 직선 연결):

4개 다이아몬드 마커를 직선으로 연결:

◆ (#E69F00) 4월
"킥오프" (20pt Bold #1A365D)
"교과운영위 논의" (16pt #2D3748)

→ 직선 화살표 →

◆ (#0072B2) 6-7월
"교수법 워크숍" (20pt Bold #1A365D)
"희망자 대상" (16pt #2D3748)

→ 직선 화살표 →

◆ (#1A365D) 9월
"시범 운영" (20pt Bold #1A365D)
"2-3개 과목" (16pt #2D3748)

→ 직선 화살표 →

◆ (#2D3748) 12월
"평가 및 환류" (20pt Bold #1A365D)
"결과 검토" (16pt #2D3748)

**하단 강조 박스** (#0072B2 outline, white fill):
"시범 운영 결과에 따라 조정 가능" (20pt Bold #0072B2)

**좌상단** (14pt #0072B2): InnoEdu 2031

White background only. Straight arrows only.

## Style Rules
- Background: #FFFFFF only
- 수평 타임라인, 직선만 사용
- 다이아몬드 마커 4색 구분

## Negative
no dark background, no curved timelines, no 3D,
no complex flow, no pressure language

## Fallback Layout
4칸 수평 박스:
[4월 킥오프] → [6-7월 워크숍] → [9월 시범] → [12월 평가]

## Self-Validation
✓ 단어수: ~260 (≤400)
✓ 색상: 4개 (≤5)
✓ 아이콘: 4개 다이아몬드 (≤4)
✓ 복잡도: MED
✓ 핵심메시지: 1개 (단계별 검증)
✓ Fallback: 설계됨

## Review Status
READY