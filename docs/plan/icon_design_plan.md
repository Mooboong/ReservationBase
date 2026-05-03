# 합주인(Hapju-in) 아이콘 디자인 전략 및 프롬프트

'합주인' 서비스의 본질인 **[음악/합주] + [공정함/질서]**를 시각화하기 위한 아이콘 컨셉과 Nano Banana용 프롬프트를 제안합니다.

## 1. 아이콘 컨셉 브레인스토밍

### 컨셉 A: The Harmonic Balance (조화로운 균형)
- **설명:** '공정함'을 상징하는 저울(Scale)과 음악을 상징하는 음표(Note)를 결합.
- **상징:** 예약 시스템의 핵심인 '자원의 공정한 분배'를 가장 직관적으로 표현.

### 컨셉 B: The Essential Jack (본질적인 연결)
- **설명:** 합주실의 필수 요소인 '6.3mm 오디오 잭(Jack)'의 단면이나 형태를 기하학적으로 변형.
- **상징:** 사용자와 공간을 연결하고, 질서(단면의 층)를 부여하는 시스템의 본질.

### 컨셉 C: The Orderly Wave (질서 있는 파형)
- **설명:** 역동적인 사운드 파형(Waveform)이 시스템의 규칙에 따라 정교한 그리드 안에서 정돈된 모습.
- **상징:** 무분별한 선착순 예약이 아닌, 시스템에 의해 관리되는 안정감.

---

## 2. Nano Banana용 프롬프트 (Black & Purple)

아래 프롬프트들을 Nano Banana에 입력하여 결과물을 확인해 보세요. 디자인 시스템(`docs/design.md`)의 컬러 가이드를 포함했습니다.

### [프롬프트 1] 컨셉 A - 미니멀 저울 & 음표 결합
> **Prompt:** Minimalist app icon design for a music reservation service. A stylized balance scale combined with a musical eighth note symbol. Use a vibrant purple gradient (#A855F7) on a pure black (#000000) background. High contrast, sharp edges, 3D glassmorphism touch with soft purple glow. 4k, professional UI/UX asset.

### [프롬프트 2] 컨셉 B - 기하학적 오디오 잭 (추상화)
> **Prompt:** Modern geometric icon of a 6.3mm audio jack head, viewed from a top-down abstract perspective. Concentric circles representing different contact rings, glowing in neon purple (#A855F7). Pure black background. Futuristic, sleek, metallic finish. High resolution, high contrast.

### [프롬프트 3] 컨셉 C - 정돈된 사운드 파형
> **Prompt:** Modern logo icon, three vertical sound wave bars of varying heights inside a rounded square container. The middle bar is the tallest. Glowing purple color palette (#A855F7) against a deep black background. Minimalist, clean lines, professional branding style.

---

## 3. 아이콘 제작 후 가이드

이미지가 생성되면 다음 단계를 추천합니다:
1. 가장 마음에 드는 이미지를 1024x1024 사이즈로 다운로드합니다.
2. [Real-ESRGAN](https://arc.tencent.com/en/ai-gentlemans) 같은 업스케일러로 해상도를 높입니다.
3. `assets/` 폴더를 만들어 저장해주시면 제가 `index.html`에 파비콘 및 OG 이미지 코드를 적용하겠습니다.
