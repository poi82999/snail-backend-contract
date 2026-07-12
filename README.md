# snail-backend-contract

Snail 백엔드의 **공개 API 계약 산출물** 미러. 백엔드 소스는 비공개 저장소(`snail_backend_specification`)에 있고, 이 저장소는 프론트엔드 클라이언트(iOS / owner_web / beta_web / admin_web)가 타입을 생성할 수 있도록 계약 파일만 공개한다.

GitHub Pages로 서빙되며, 프론트의 `openapi-typescript` / `sync-backend-docs` 가 아래 URL에서 파일을 받는다.

- `openapi.json` — OpenAPI 3.1 스펙 (SSOT, `generate:types:remote` 소스)
- `frontend_app.ai.txt` · `api_cookbook.ai.txt` · `llms.txt` · `local_onboarding.md` — API 소비용 컨텍스트 문서

Pages URL: `https://poi82999.github.io/snail-backend-contract/openapi.json`

> 자동 생성물. 직접 수정하지 말 것 — 백엔드에서 재생성 후 이 저장소로 퍼블리시한다.
