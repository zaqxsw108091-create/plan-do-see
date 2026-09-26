# 플랜두씨 다이어리 (과제 6)

- `index.html` — 과제 제출용 페이지. 로그인 없음. 누구나 링크로 접근 가능.
- `private.html` — 개인용 페이지. Firebase 로그인(이메일/비밀번호) 후 본인 데이터만 보임.
- `firestore.rules` — Firestore 보안 규칙(콘솔에 그대로 붙여넣기).
- `contracts/pds-schema-v2.json` — 데이터 스키마 문서.

둘 다 같은 Firebase 프로젝트(plan-do-see-bd6d1)의 Firestore를 씁니다.
`index.html`은 로그인 없이 공개 컬렉션에, `private.html`은 로그인한 사람의 UID 하위 경로에만 접근합니다.
