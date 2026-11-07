# 야식 참는 기계

야식이 땡길 때 버튼을 누르면 명언 또는 팩폭 한마디를 랜덤으로 보여주는 정적 웹앱입니다. 이름을 입력하면 문구 앞에 이름을 붙여서 더 생생하게 보여줍니다.

순수 HTML/CSS/JS로만 되어 있고, 빌드 과정이 없습니다.

## 로컬에서 보기

`index.html`을 브라우저로 바로 열면 됩니다. 또는:

```bash
npx serve .
```

## Vercel에 배포하기

이 저장소를 Vercel에 연결하면 별도 빌드 설정 없이 그대로 배포됩니다 (정적 사이트, `index.html`이 루트에 있음).

1. [vercel.com](https://vercel.com)에서 New Project
2. 이 GitHub 저장소 선택
3. Framework Preset: Other (정적 파일 그대로 서빙)
4. Deploy

또는 Vercel CLI 사용:

```bash
npm i -g vercel
vercel
```
