# STRUCTURE — interior-sample (ONJIP 온집)

```
interior-sample/
├── index.html        # 단일 파일(인라인 CSS/JS)
├── .assetsignore
├── README.md
├── STRUCTURE.md
└── CHANGELOG.md
```

## index.html 섹션 순서
1. `.topnav` 상단 수평 내비(로고 + 시공사례/시공과정/회사소개/문의 + 견적문의 버튼)
2. `#home` 히어로(좌 카피+CTA / 우 **before-after 슬라이더**)
3. `#work` 시공 사례 — 필터 + **케이스별 before-after 슬라이더 + 메타(공간·평형·기간·예산대)**
4. `#process` 시공 과정 — 번호 단계(상담→실측·견적→설계→시공→준공·검수→A/S)
5. `#about` 회사 소개·보증(하자보수 등 신뢰 신호)
6. `#contact` 견적 **문의** 폼(Formspree)
7. `footer` + `.mbar` 모바일 하단바(전화·카톡·견적문의)
8. `<script>` before-after 드래그(포인터/터치), 필터, 모바일 메뉴, 스크롤 리빌(데스크탑)

## before-after 슬라이더(.ba)
base=시공후(full), overlay=시공전(clip-path inset로 좌측만), 핸들 드래그로 분할 이동. pointer 이벤트(마우스·터치 공용).

## 팔레트/토큰
`--sand:#E9E3D7; --paper:#F3EFE7; --ink:#23211D; --petrol:#2E5159; --line:#D9D2C4; --grey:#6E6A60`
타입: Archivo(디스플레이·숫자) + Pretendard.
