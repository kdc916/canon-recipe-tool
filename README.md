📷 Canon Recipe Generator + Fuji Preset Overlay (v9.1 PATCHED)

한 장(타겟만) 또는 두 장(원본+타겟) 사진을 넣으면, **Canon Picture Style Editor(PSE)**에 입력 가능한 형태로

Contrast / Saturation / Color Tone

Tone Curve(5pt)

Specific Colors(6-axis H/S/L)
를 자동으로 산출합니다.

또한 선택 옵션으로 Fuji Preset Overlay(B안) 기능을 제공하며, 분석 결과에 “후지 감성”을 강도(%)로 안전하게 블렌딩할 수 있습니다.

✅ 주요 기능

1장 모드(타겟만): 원하는 색감의 참고사진 1장으로 빠르게 레시피 추정

2장 모드(원본+타겟): 내 카메라 기본톤(원본) → 목표톤(타겟) 매칭으로 정교한 레시피 산출 (권장)

AI 자동 모드(선택): 인물/풍경 등을 감지해 베이스(표준/뉴트럴/인물/풍경)를 추천

Fuji Preset Overlay(B안): Provia/Astia/Velvia/Classic Chrome/Classic Negative 등 프리셋 감성을 20~45% 블렌딩 추천

결과를 요약/전체 리포트로 출력하고 복사 버튼 제공

🧩 v9.1 PATCHED 변경점(중요)

[FIX] 2장 모드에서 AI가 ‘타겟’ 이미지를 보고 판별하도록 순서 오류 수정
(기존에는 타겟을 그린 뒤 원본을 다시 그려 AI가 원본을 보고 판별하는 문제가 발생 가능)

[호환성] createImageBitmap() 실패 시 fallback(Image 로딩) 추가

[UX] Fuji Preset이 Off면 프리셋 강도 슬라이더 비활성화

[품질] 1장 모드 중립축(S) 보수화(과한 색축 움직임 완화)

🛠 사용 방법

페이지를 열고

타겟(원하는 색감) 사진을 업로드

필요하면 원본(기본 톤) 사진도 업로드(2장 모드)

모드/해상도/Fuji 프리셋/강도를 선택

⚡ 분석 시작 → 결과를 복사

Canon **Picture Style Editor(PSE)**에서 아래 순서로 입력

Base

Contrast / Saturation / Color Tone

Tone Curve(5pt)

Specific Colors(6-axis H/S/L)

🎛 추천 세팅 가이드(실전)

정확도 우선: 2장 모드 권장(가능하면 같은 장소/피사체/빛 조건)

Fuji Overlay 강도: 보통 **20~45%**가 가장 자연스럽게 “후지 느낌”만 얹힘

과해 보이면: Saturation -1 → Color Tone -1 순으로 먼저 내려보는 게 안전

⚠️ 주의 / 한계

이 도구는 “참고 레시피 생성기”이며, 실제 카메라/렌즈/조명/WB에 따라 차이가 납니다.

타겟 이미지가 극단적으로 어둡거나 밝으면 톤 커브가 단순화될 수 있습니다.

브라우저 환경(특히 모바일/사파리)에 따라 성능 차이가 있을 수 있습니다.

🔒 Privacy

업로드한 이미지는 브라우저 로컬에서만 처리됩니다.

서버 업로드/저장은 하지 않습니다.

📄 License

Copyright (c) 2026 <YOUR Dongcheol Kim>
All rights reserved.

You may view and study this repository for personal, non-commercial purposes.
You may not use, copy, modify, merge, publish, distribute, sublicense, or sell
any part of this software or its derivatives without prior written permission
from the copyright holder.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND. IN NO EVENT
SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR
OTHER LIABILITY, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR
THE USE OR OTHER DEALINGS IN THE SOFTWARE.

README (English)
📷 Canon Recipe Generator + Fuji Preset Overlay (v9.1 PATCHED)

Drop one target photo (or two photos: original + target) and this tool generates a Canon Picture Style Editor (PSE)-friendly recipe:

Contrast / Saturation / Color Tone

Tone Curve (5 points)

Specific Colors (6-axis H/S/L)

Optionally, it provides a Fuji Preset Overlay (Plan B) that blends a Fuji-like “vibe” into the analysis result with a safe strength (%) control.

✅ Features

1-shot mode (Target only): quick recipe estimation from a single reference look

2-shot mode (Original + Target): more accurate mapping from your camera’s base look → target look (recommended)

AI Auto mode (optional): detects portrait/landscape-ish content to recommend a base style (Standard/Neutral/Portrait/Landscape)

Fuji Preset Overlay (Plan B): Provia/Astia/Velvia/Classic Chrome/Classic Negative, etc.
Suggested blend strength: 20–45%

Outputs both Summary and Full Report, with Copy buttons

🧩 What’s new in v9.1 PATCHED (Important)

[FIX] In 2-shot mode, AI classification now analyzes the “Target” image (order-of-operations bug fix)
(Previously, the canvas could be overwritten by the original photo before AI detection.)

[Compatibility] Added fallback when createImageBitmap() fails

[UX] Preset Strength slider is disabled when Fuji Preset is OFF

[Quality] Slightly more conservative neutral baseline for 1-shot mode

🛠 How to use

Open the page

Upload a Target image (the look you want)

(Optional, recommended) Upload an Original image (your neutral/base look) in 2-shot mode

Choose mode / resolution / Fuji preset / strength

Click ⚡ Analyze → Copy the result

In Canon Picture Style Editor (PSE), enter in this order:

Base

Contrast / Saturation / Color Tone

Tone Curve (5pt)

Specific Colors (6-axis H/S/L)

🎛 Practical tips

Best accuracy: use 2-shot mode with similar scene/subject/lighting conditions

Fuji Overlay strength: 20–45% usually feels the most “natural”

If it looks too strong: try reducing Saturation first, then Color Tone

⚠️ Notes / Limitations

This is a “recipe generator” and results vary by camera, lens, lighting, and WB.

Extremely dark/bright targets may simplify the curve output.

Performance may vary depending on browser/device (especially mobile Safari).

🔒 Privacy

Images are processed locally in your browser.

No server upload/storage.

📄 License

Copyright (c) 2026 <YOUR Dongcheol Kim>
All rights reserved.

You may view and study this repository for personal, non-commercial purposes.
You may not use, copy, modify, merge, publish, distribute, sublicense, or sell
any part of this software or its derivatives without prior written permission
from the copyright holder.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND. IN NO EVENT
SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR
OTHER LIABILITY, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR
THE USE OR OTHER DEALINGS IN THE SOFTWARE.
