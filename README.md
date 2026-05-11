# 연구과제 통합 예산관리

연구과제 통합 예산관리 페이지의 정적 HTML 데모입니다.

## 데모

- 배포 URL: https://changminim.github.io/research-budget/

## 구성

- `index.html` — 단일 페이지 정적 HTML (외부 의존성 없음, Google Fonts만 CDN 사용)

## 로컬 미리보기

저장소를 클론한 뒤 `index.html`을 브라우저로 바로 열거나, 간단한 정적 서버로 띄울 수 있습니다.

```bash
git clone https://github.com/ChangminIm/research-budget.git
cd research-budget
# Python이 설치되어 있다면
python -m http.server 8000
# http://localhost:8000 접속
```

## 업데이트 방법

`index.html`을 수정한 뒤 다음을 실행하면 GitHub Pages가 자동으로 재배포합니다.

```bash
git add index.html
git commit -m "Update budget page"
git push
```
