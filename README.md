# SignalFlywheel Landing + Thumbnails

이 폴더에는 **바로 배포 가능한 랜딩 페이지(HTML/CSS)**와 **썸네일/OG 이미지(SVG)**가 포함되어 있습니다.

## 포함 파일
- `index.html` — 단일 랜딩 페이지
- `styles.css` — 스타일
- `assets/thumb_variant*.svg` — YouTube 썸네일 1280×720 (3종)
- `assets/og_variant*.svg` — Open Graph 이미지 1200×628 (2종)

## 실행(로컬)
그냥 `index.html`을 브라우저에서 열면 됩니다.

## 배포(추천: Netlify / Vercel)
### Netlify
- 새 사이트 → 이 폴더를 드래그앤드롭 업로드

### Vercel
- 정적 사이트로 배포 (Git 연결 권장)

## 폼 연동(3가지 중 택 1)
1) **스티비**
- 스티비에서 구독 폼 생성 → action URL을 HTML 폼의 `action`에 붙이기

2) **Mailchimp**
- Audience → Signup forms → Embedded form → action URL 복사

3) **Google Form/Typeform + Zapier/Make**
- 폼 응답 → Airtable/Notion DB 저장 → 메일 발송 자동화

> 현재 `index.html` 폼은 데모(alert)로 되어 있습니다. 실제 action으로 교체하세요.

## OG 이미지 교체
- `index.html`의 `og:image` 값을 원하는 파일로 바꾸면 됩니다.
- SVG를 PNG로 내보내고 싶다면:
  - Figma에서 SVG 열기 → Export PNG
  - 또는 브라우저로 열어 스크린샷(권장 X)

## 커스터마이즈 포인트
- 타깃/오퍼가 정해지면:
  - Hero 문장, 구성 섹션, Pricing/FAQ 문구만 바꿔도 전환율이 확 올라갑니다.
