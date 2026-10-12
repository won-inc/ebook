# ebook

ROUTE 무료 전자책 배포용 **중간 다리** 페이지 모음.

| 경로 | 자료 | 목적지 |
|---|---|---|
| `/core6weeks/` | 자세 교정·코어 입문 6주 프로그램 | 카페 글 21606 |
| `/machine8weeks/` | 머신 첫 헬스장 8주 운동 프로그램 | 카페 글 21581 |

## 왜 다리가 필요한가

스레드·인스타 **앱 안의 브라우저는 파일 받기를 못 한다.**
네이버 카페 첨부 응답이 `content-disposition: attachment` + `application/octet-stream`
+ `x-content-type-options: nosniff` 로 와서 화면에 띄울 수도 없다.
(권한 문제가 아니다 — 비회원도 HTTP 200 으로 전부 받는다)

그래서 **사람이 버튼을 눌러** 외부 브라우저로 나가게 한다.
자동 이동은 메타 웹뷰가 조용히 버리므로 쓰지 않는다.
스킴이 막혀도 「주소 복사」로 끝까지 갈 수 있다.

## 이름 규칙

**폴더 이름에 기간을 붙인다** — `core6weeks` · `machine8weeks`.
자료가 늘어도 겹치지 않게 하기 위해서다.

> ⚠️ `won-inc/8weeks` 저장소가 따로 있다. 2026-10-08 에 먼저 만든 것으로,
> 8주 전자책 DM 이 이미 그 주소로 나갔다. **죽이면 안 되므로 그대로 둔다.**
> 새 DM 은 전부 이쪽(`ebook`)을 쓴다.

원본: `marketing` 저장소의
`fitness/topics/20260923-hugh-jackman-4week-block/instagram/전자책_DM/bridge/`
