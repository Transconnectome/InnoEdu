# S2 Prompt — 왜 조정하는가

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

서울대학교 심리학과 교과개편 근거 자료.

**상단 제목** (28pt Bold #1A365D):
왜 조정하는가: 검증된 데이터

**4칸 수평 카드** (각 카드 rounded rectangle, thin outline):

카드1 (#1A365D outline):
"문헌 기반" (20pt Bold #1A365D)
"600편" (32pt Bold #E69F00)
"체계적 분석, Tier 1 72.2%" (16pt #2D3748)

카드2 (#0072B2 outline):
"PBL 교수법" (20pt Bold #0072B2)
"메타분석 검증" (32pt Bold #E69F00)
"학업 성취 유의미 향상" (16pt #2D3748)

카드3 (#E69F00 outline):
"학부 연구 참여" (20pt Bold #E69F00)
"졸업률 2-10배" (32pt Bold #E69F00)
"참여 vs 비참여 비교" (16pt #2D3748)

카드4 (#2D3748 outline):
"FLC 교수법 지원" (20pt Bold #2D3748)
"2년 이상 지속" (32pt Bold #E69F00)
"자발적 참여 기반" (16pt #2D3748)

**하단** (16pt #0072B2):
상세 문헌 목록은 킥오프 미팅에서 공유됩니다

**좌상단** (14pt #0072B2): InnoEdu 2031

White background. Clean flat card layout.

## Style Rules
- Background: #FFFFFF only
- 4개 카드 동일 크기, 가로 나란히
- outline만 사용, fill 없음

## Negative
no dark background, no 3D, no glossy,
no marketing claims, no exaggerated effects

## Fallback Layout
2x2 그리드:
[문헌 600편] [PBL ES 0.44]
[졸업률 2-10배] [FLC 2년]

## Self-Validation
✓ 단어수: ~280 (≤400)
✓ 색상: 4개 (≤5)
✓ 아이콘: 0개 (≤4)
✓ 복잡도: LOW
✓ 핵심메시지: 1개 (데이터 기반 판단)
✓ Fallback: 설계됨

## Review Status
READY