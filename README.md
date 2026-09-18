# bible-site — bible.lupa.kr

"주간 성경퀴즈" (은천교회 주간성경공부 제출 관리 시스템)를 **다른 교회에 소개하는 랜딩 페이지**. 정적 HTML 한 장.

- 시스템 본체: `DEV/euncheon-bible` (Express + React, 맥미니 :3000) → 공개 주소 `https://euncheon-bible.lupa.kr` (Cloudflare Tunnel, `euncheon-bible/deploy/cloudflare-tunnel/`)
- 이 페이지: GitHub Pages + `CNAME`(bible.lupa.kr). Cloudflare DNS에 `bible CNAME paeyoungpark-web.github.io`.
- 다른 교회 인스턴스는 `○○-bible.lupa.kr` 패턴으로 터널 인그레스만 추가.

## 카피 원칙
- 시스템이 실제로 하는 것만 쓴다: 이름·회차 인식 → 출석부 기록·집계. **답안 채점은 아직 없음** (FAQ에 명시).
- 숫자는 백서 기준: 170명, 52주, 2026-05 운영 시작.
- 가격: 무료 / 실비. 구체 금액은 적지 않음 (문의 시 협의).
