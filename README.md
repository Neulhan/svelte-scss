# svelte-scss template

## how to start
```
npx degit neulhan/svelte-scss my-project-name 

cd my-project-name

npm i

npm run dev
```


## npm dependencies
- svelte
- svelte-preprocess
- node-sass


## 제작배경
최근 `한오이탑`이나 `Legal OCR Beta` 같은 svelte 프로젝트 여러가지를 진행했다.  
그런데 매 프로젝트마다 해야하는 초기 세팅이 너무 불필요하게 반복되었다.  
그게 귀찮아서 간단한 몇가지를 추가해서 템픞릿으로 제작했다.  

## 용도


- svelte 내부 style에서 scss 를 사용할 수 있는 것이 주 용도이다.
- 그 밖에 내가 선호하는 세팅을 몇가지 추가했다
  - Noto Sans KR 웹폰트
  - 커스텀 css 초기화 코드
  - 자주 쓰던 scss mixin 및 변수들
  - 깔끔한 첫 페이지
  - 커스텀 favicon 🔨(망치?)
