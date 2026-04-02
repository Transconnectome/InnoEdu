# S1 Prompt — BMBM 프레임워크

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

서울대학교 심리학과 교과개편 안내 슬라이드.

**상단 제목** (28pt Bold #1A365D):
BMBM 프레임워크: 39개 과목의 체계적 재편성

**4칸 수평 카드** (동일 크기, 색상 구분):

dark navy 박스: Brain 뇌 28% (20pt Bold white)
11개 과목 (16pt white)

blue 박스: Mind 마음 20.5% (20pt Bold white)
8개 과목 (16pt white)

orange 박스: Behavior 행동 31% (20pt Bold white)
12개 과목 (16pt white)

dark gray 박스: Method 방법 20.5% (20pt Bold white)
8개 과목 (16pt white)

**하단 서브 텍스트** (20pt #2D3748):
신설 4개(N1-N4) + 개편 10개(E1-E10) = 14개 과목 조정

**좌상단** (14pt #0072B2): InnoEdu 2031
**우하단** (14pt #2D3748): 서울대학교 심리학과

White background only. Clean flat design. No icons.

## Style Rules
- Background: #FFFFFF only
- 4개 박스 동일 크기 가로 배열
- 각 박스 rounded rectangle with soft fill

## Negative
no dark background, no 3D, no glossy, no poster style,
no circular diagrams, no marketing language

## Fallback Layout
4칸 수평 박스:
[Brain 28%] [Mind 20.5%] [Behavior 31%] [Method 20.5%]

## Self-Validation
✓ 단어수: ~200 (≤400)
✓ 색상: 4개 (≤5)
✓ 아이콘: 0개 (≤4)
✓ 복잡도: LOW
✓ 핵심메시지: 1개 (BMBM 구조)
✓ Fallback: 설계됨

## Review Status
READY