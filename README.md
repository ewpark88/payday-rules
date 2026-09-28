# payday-rules

입금캘린더 앱이 하루 한 번 받아 가는 **공개 규칙 파일**입니다.

- `rules.json` — 공휴일·가맹점 우대수수료율·세액공제 규칙을 담은 봉투
  `{ format, version, sha256, rules }`. 앱은 `rules` 원문의 SHA-256 이 맞을 때만 씁니다.
- 사용자 데이터는 없습니다. 앱은 이 파일을 받기만 합니다.
- 이 저장소는 `payday-calender` 저장소의 `rules.yml` 워크플로가 자동으로 갱신합니다.
  손으로 고치지 마세요.
