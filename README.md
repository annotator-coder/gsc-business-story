# GS칼텍스 사업부문 스크롤텔링

여수공장의 생산공정과 주요 제품을 통해 GS칼텍스의 사업과 경쟁력을 소개하는 인터랙티브 웹 브로셔입니다.

- 라이브: https://gsc-business-story.vercel.app
- 언어: 국문(`/`) · 영문(`/en`) · 일문(`/ja`) · 중문(`/zh`)
- 구성: 정유 · 방향족 · 올레핀 · 폴리머 · 베이스오일 · 윤활유 · 공정 · 회사 소개, 인덱스(`/menu`)
- 인쇄용: `pdf/business-story-{ko,en,ja,zh}.html`

## 로컬 실행

빌드 과정이 없는 정적 HTML입니다.

```bash
npx serve .        # 또는 python3 -m http.server
```

URL을 `.html` 없이 쓰려면(`cleanUrls`) Vercel CLI의 `vercel dev`로 실행하세요.
