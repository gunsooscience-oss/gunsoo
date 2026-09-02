# My Site

GitHub Pages로 배포되는 정적 HTML 사이트.

## 배포 방법

`main` 브랜치에 push 하면 GitHub Actions가 자동으로 배포합니다.

```bash
git add .
git commit -m "update"
git push
```

## 구조

- `index.html` — 사이트 첫 페이지
- `.github/workflows/deploy.yml` — 자동 배포 설정
- `.nojekyll` — Jekyll 처리 비활성화 (`_`로 시작하는 파일/폴더 보존)

새 페이지는 `about.html` 처럼 파일을 추가하면 `/about.html` 경로로 접근됩니다.
