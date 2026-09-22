# obsidian-comment-repository

옵시디언 볼트 `개똥이 머릿속` 의 코멘트 슬랙 알림에 붙는 **`옵시디언에서 열기 →` 중계 페이지**입니다.

슬랙은 `obsidian://` 링크를 눌리게 해 주지 않아서, 링크가 이 페이지를 한 번 거쳐
`obsidian://open?vault=…&file=…` 로 넘어갑니다. 열리는 건 **누른 사람 컴퓨터의 옵시디언**입니다.

```
https://hyerin-seo.github.io/obsidian-comment-repository/#file=<노트 경로>&v=<볼트1>&v=<볼트2>
```

- 사람마다 볼트 폴더 이름이 달라서 링크에 볼트 후보를 다 담고, 처음 한 번 고른 볼트를 그 브라우저에 기억합니다 (localStorage).
- 볼트 이름·노트 경로는 주소의 `#` 뒤에만 있습니다. `#` 뒤는 브라우저가 서버에 보내지 않으므로 GitHub 에 남지 않습니다.
- 이 저장소에는 페이지 한 장(`index.html`)뿐이고 노트 내용은 없습니다.
- 링크를 만드는 쪽: 볼트의 `.obsidian/plugins/claude` (💬 코멘트 · @언급) — 설정의 `바로 가기 주소 틀`.
