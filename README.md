# joonggaetalk-home

중개톡 공식 소개 페이지 (주황 시안 v3). 단일 HTML 파일로, 이미지까지 모두 인라인이라 별도 자산 없이 동작합니다.

- 공개 주소: https://puppy2848-ctrl.github.io/joonggaetalk-home/
- 예정 도메인: https://joonggaetalk.com

## 브랜치

| 브랜치 | 용도 |
|---|---|
| `main` | 원본 보관 |
| `gh-pages` | GitHub Pages가 실제로 서비스하는 브랜치 (index.html) |

## 수정할 때

1. `index.html`을 고칩니다.
2. `main`에 커밋·푸시한 뒤, 같은 파일을 `gh-pages` 브랜치에도 올립니다.

```bash
git checkout main && git add index.html && git commit -m "내용 수정" && git push
git checkout gh-pages && git checkout main -- index.html && git commit -am "배포" && git push
```

반영까지 1분 안팎 걸립니다.
