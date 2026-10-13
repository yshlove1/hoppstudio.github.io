# 새 앱 추가 방법

1. `sketchbook-defense/` 폴더를 통째로 복사해서 새 앱 폴더명으로 바꿉니다. (예: `new-game/`)
2. 폴더 안 `index.html`, `privacy.html`에서 앱 이름, 소개, 방침 내용을 수정합니다.
   - 광고/분석 SDK를 쓰면 `privacy.html`의 3번 항목에 SDK와 수집 항목을 반드시 적습니다.
3. 루트 `index.html`의 `app-list`에 `<li>` 한 줄을 추가합니다.
4. 커밋 & 푸시하면 Pages에 자동 반영됩니다.

Play Console에는 앱별로 아래 URL을 입력합니다.
- 웹사이트: 스튜디오 루트 주소
- 개인정보처리방침: `<루트 주소>/<앱 폴더>/privacy.html`
