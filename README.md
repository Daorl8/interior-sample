# interior-sample — ONJIP 온집 (인테리어 시공)

이피웹(YIPI WEB) 포트폴리오용 ⑥번 샘플. 인테리어 시공·리모델링 회사.

- **매트릭스 셀:** 멀티섹션 · 포트폴리오(시공사례) · **before-after 드래그 슬라이더(시공 전/후 비교, 마지막 미점유 인터랙션)** · 필터 · 신뢰(시공과정·보증) 섹션
- **무드:** 웜 샌드+차콜+**페트롤(틸) 액센트** — 기존 10종과 안 겹치는 새 계열. Archivo 디스플레이 + Pretendard.
- **정직 라벨:** 견적 "문의" 폼(즉시 견적 아님), 전화·카카오톡 상담 연결. 모바일 하단바=전화·카톡·견적문의(PC CTA와 통일).
- **before/after 이미지:** 동일 공간 페어가 아닌 placeholder(실납품 시 고객 제공 전/후 사진으로 교체).
- **앵커 보정:** `scroll-padding-top` 적용. 실제 .assetsignore 포함 + 배포 후 /.git/config 404 확인.

배포: Cloudflare Workers. Formspree `YOUR_FORM_ID` 치환 필요.
