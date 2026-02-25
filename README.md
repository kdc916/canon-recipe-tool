# 📷 Canon Recipe & 3D LUT Generator (v8.1)
> Canon Picture Style Editor(PSE)용 **레시피 자동 생성** + **3D LUT(.cube) 동시 추출**  
> 브라우저에서 바로 실행되는 “복붙-완료” 워크플로우. 초보자는 **요약 보기**만 따라가면 끝.

---

## 🌟 핵심 한 줄
- **원본(기본 톤)** + **타겟(원하는 색감)** 2장을 넣으면 → **PSE 입력값(베이스/대비/톤커브/6색축)** + **3D LUT(.cube)** 를 뽑아줍니다.

---

## 🧭 Demo / Live
https://kdc916.github.io/canon-recipe-tool/

---

## ✅ Features
### 🇰🇷 한글
- **2장 비교 분석**: 원본(Standard/Neutral 권장) ↔ 타겟(레퍼런스 색감)
- **AI 자동 모드(하이브리드)**  
  - BlazeFace: 얼굴 감지 → 인물 톤 최우선  
  - MobileNet: 얼굴 없으면 풍경/사물 분류
- **수동 모드 토글**: `AI 자동 / 인물 / 풍경 / 스냅 / 야경`
- **대용량 이미지 안정성**: 최대 해상도(기본 1024px) 리샘플링으로 프리징 방지
- **Web Worker 분석**: 무거운 픽셀 루프를 Worker로 분리해 UI 끊김 최소화
- **결과 탭 UI**  
  - **요약 보기**: 초보자용 핵심 값만  
  - **전체 보기**: 상세 리포트(검증/진단 포함)
- **원클릭 출력**: 요약 복사 / 전체 복사 / 3D LUT(.cube) 다운로드

### 🇺🇸 English
- **Two-image analysis**: Original (baseline) ↔ Target (desired look)
- **Hybrid AI Auto Mode**
  - BlazeFace: detects faces → portrait-friendly base
  - MobileNet: if no faces → scene/object classification
- **Manual Mode Toggle**: `AI Auto / Portrait / Landscape / Snap / Night`
- **Large-image safety**: resampling (default 1024px max) to prevent freezing
- **Web Worker processing**: heavy loops off the main thread for smooth UI
- **Result Tabs**: Summary View / Full View
- **One-click outputs**: Copy Summary / Copy Full / Download 3D LUT (.cube)

---

## 🧑‍🍳 How to Use
### 🇰🇷 한글
1) **원본 사진** 업로드 (Standard/Neutral 톤 권장)  
2) **타겟 사진** 업로드 (원하는 영화/필름 색감 레퍼런스)  
3) 모드 선택(자동/수동) → **분석 시작**  
4) 결과의 **Base / Contrast / Tone Curve / Specific Colors(6축)** 를 **Canon PSE**에 입력  
5) 필요하면 **3D LUT(.cube)** 를 다운로드해 DaVinci / Premiere 등에 적용

### 🇺🇸 English
1) Upload **Original** (Standard/Neutral recommended)  
2) Upload **Target** (film/cinematic reference)  
3) Select mode → **Run Analyze**  
4) Enter **Base / Contrast / Tone Curve / Specific Colors** into **Canon PSE**  
5) Optionally download **.cube LUT** for DaVinci / Premiere / etc.

---

## 🧾 Output Format (What you get)
- **Summary View**
  - Base
  - Contrast
  - Tone Curve (5 points)
  - Specific Colors (6-axis H/S/L)
- **Full View**
  - Detailed recipe report (reasoning + diagnostics)
- **3D LUT**
  - `.cube` file generated from tone LUT + 6-axis adjustments

---

## ⚠️ Tips / Notes
### 🇰🇷 한글
- 타겟이 **너무 어둡거나/너무 밝으면** 결과가 단순화될 수 있습니다.
- 초보자에게 가장 안정적인 조합은:
  - 두 사진 모두 **중간톤이 많고**
  - **구도/피사체가 비슷한** 사진
- 브라우저/기기 성능 차이가 있으니, 느리면 **해상도 1024px** 권장.

### 🇺🇸 English
- Extremely dark/bright targets can produce simplified results.
- Best stability:
  - plenty of midtones
  - similar subjects/composition between Original and Target
- If performance is slow, keep **1024px**.

---

## 🛠 Tech Stack
- Frontend: Vanilla **HTML/CSS/JavaScript**
- AI: **TensorFlow.js** + **BlazeFace** + **MobileNet**
- Compute: **Web Worker** + Canvas sampling

---

