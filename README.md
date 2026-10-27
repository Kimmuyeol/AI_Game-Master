# 모닥불 — AI 게임 마스터 TRPG

- 원본 Artifact: https://claude.ai/artifact/4juXePL3sf7teDC9BBTYkN
- 가져온 버전: `1793102310-5cb6` (2026-10-28)
- 런타임 contract: `0.2.90`
- capabilities: `{"db":{},"sample":{},"user":{}}`

`index.html` 하나로 된 페이지예요. 캠페인·캐릭터·이야기 기록은 Artifact의 공유 DB에 있어서
이 파일만 브라우저로 열면 저장·AI GM 기능이 동작하지 않아요. 수정한 뒤에는 위 URL로 다시 게시해야 해요.

## data/

2026-10-28에 Artifact DB에서 내려받은 백업이에요 (경로는 DB 컬렉션 구조 그대로).

- `campaigns/<id>.json`: 캠페인 설정
- `campaigns/<id>/chars/`: 플레이어 캐릭터
- `campaigns/<id>/log/`: 이야기 기록
- `campaigns/<id>/memory/`: GM 기억 장부(`ledger`), GM 비밀 노트(`secret`, 스포일러)
