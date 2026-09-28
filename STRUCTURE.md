# STRUCTURE — 이룸미당 (EROOM MIDANG · @eroom2000)

의정부 수제 찰떡(말랑이떡)·찹쌀 인절미 전문점 **9.9 스탠다드 원페이지** 샘플. 방향 = A 모던 브랜드(코발트 블루+화이트) — 다올 선택 2026-09-28. (v0.x 링크허브 → v1.0 원페이지 재구성)

```
/ (배포 루트, CF [assets] directory="./")
├─ index.html           단일 파일 (인라인 CSS/JS, 모바일 우선)
├─ er-logo.webp         로고 전체 블루 키잉 → 흰색 알파 (히어로)
├─ er-grain.webp        쌀알 심볼 알파 (헤더 마크·푸터)
├─ er-trio.webp         쑥·단호박·초당 3종 4:3 (히어로 사진·갤러리)
├─ er-lineup.webp       색깔별 줄 세움 (메뉴·갤러리)
├─ er-white.webp        하양이 클로즈업 (갤러리)
├─ er-ssuk.webp         쑥말랑이 접시 (갤러리)
├─ er-cups.webp         파란 스티커 컵 포장 (갤러리)
├─ er-injeolmi.webp     쑥 인절미 4:3 (갤러리)
├─ er-gift.webp         리본 선물 상자 (선물·답례)
├─ er-grainfill.webp    쑥말랑이떡 접시 세로 502×702 (소개 · 쌀알 mask)
├─ er-chodang.webp      초당말랑이떡 나무 상자 (갤러리)
├─ er-bite.webp         팥 찹쌀떡 한 입 1024×1280 (갤러리 큰 칸, 다올 제공)
├─ er-hands · er-ssuk · er-band · er-injeolmi .webp   미사용(.assetsignore 제외, 업로드 X)
├─ er-grain-blue.webp   파란 쌀알 (푸터 흰 스티커)
├─ index_v1.html        v1.0 비교용 백업 (.assetsignore 제외)
├─ paperlogy-sub.woff2  Paperlogy Bold 서브셋 21KB (OFL 1.1)
├─ favicon.png · og-eroom.jpg(1200×630)
├─ wrangler.toml · .assetsignore · CHANGELOG.md · STRUCTURE.md
└─ img/                 IG 원본 37장 (배포 제외)
```

## 섹션 / 앵커
헤더(스티키) → `#top` 히어로 → `#about` 소개(+부모님 말씀 인용) → `#menu` 메뉴 표 → `#gift` 선물·답례 → `#gallery` 갤러리 6 → `#review` 후기 5 → `#order` 주문·예약 4채널 → `#visit` 오시는 길(구글 지도) → 푸터.
- 반응형: 모바일 1열 / ≥720 갤러리 3열·후기 2열·채널 2열 / ≥960 히어로·소개·메뉴·선물·오시는길 2단, 후기 3열. 내비 링크는 ≤820에서 숨김(주문하기 버튼만).

## 디자인 토큰
- 코발트 블루 `#2D4BA3`(로고 실측, 흰 글자 7.9) · hover `#233C86` · 흰 바탕 파란 텍스트 `#1E3374`(11.8).
- 쌀눈 노랑 `#FAC661` = 밑줄·포커스 링 장식 전용(텍스트 금지).
- 쿨 라이트 `#F4F6FB` · 라인 `#E1E6F1` · 잉크 `#151C33` · 보조 `#4A5270`(7.7).
- 폰트: 제목 Paperlogy 700(로컬 서브셋 self-host) · 본문 Pretendard(시안 CDN 무버전). 폴백 전부 산세리프. 전역 `img{height:auto}`.
- 모티프: 히어로 **표시사항 라벨**(원산지·생산·시작) — 선물 섹션 dl도 같은 선 규칙.

## 링크
스마트스토어 smartstore.naver.com/eroom2026 · 네이버 플레이스 map.naver.com/p/entry/place/2041991440 · 블로그 m.blog.naver.com/eroom2026/224308913448 · 인스타 @eroom2000 · 전화 0507-1334-3082 · 구글 지도 임베드(키 없음, 주소 쿼리).

## ⚠️ 확인/보류
- 영업시간=블로그 기준(월–토 09–17). 플레이스 9/28(월) 휴무 표시 → 임시휴무 여부 확인.
- 메뉴 = 네이버 플레이스 등록 4종만, 가격 비노출(v1.2 다올 결정). 상시/시즌 여부는 사장님 확인 전(초당은 IG상 시즌 가능성).
- 모션은 기기 '동작 줄이기' 설정과 무관하게 강제 재생(다올 지시).
- 후기 5건은 실제 네이버 방문자 리뷰(마스킹·이모지 제거·경미한 교정). 사장님께 게재 동의 확인 권장.
- 흑임자(까망이) 단독 깨끗한 사진 없음.
- 헤드리스 렌더 불가 → 배포 후 라이브 확인. 고객 인계 시 `grep lgt3232` 5곳 치환 + Pretendard self-host.
