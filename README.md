
이 프로겍트는 REACTJS + MeterialUI를 사용하는 연습을 하고 있습니다.


우선 기본 프로젝트의 틀은 아래의 동작을 진행하였습니다.


# #1 ReactJS 프로젝트 생성하기

```
$ npx create-react-app hello-meterialui
$ cd hello-meterialui
```
---

# #2 [Meterial-ui 모듈 설치하기](https://material-ui.com/getting-started/installation/)

```
$ npm install --save @material-ui/core
$ npm install --save @material-ui/icons
$ npm install --save @material-ui/styles
```
## cssbaseline & styleProvider 정보

1. [StylesProvider](https://material-ui.com/styles/advanced/#css-injection-order)

2. [CssBaseline](https://material-ui.com/components/css-baseline/#css-baseline)

---

# #3 추가 모듈 설치 하기 - Option

```
$ npm install --save styled-components
```
## [styled-components](https://www.styled-components.com/)

## [styled-components example](https://www.gatsbyjs.org/docs/styled-components/)

---

# #4 .eslint 설정 (.eslintrc.js) - Option
```
module.exports = {
  "extends": "react-app",
  "globals": {
  },
  "rules": {
      "no-console": "off",
      "no-constant-condition": "off",
      "no-unreachable": "off",
      "no-empty": "off",
      "no-useless-escape": "off",
      "no-throw-literal": "off",
      "no-unused-vars": "warn",
      "react-hooks/rules-of-hooks": "error",
      "react-hooks/exhaustive-deps": "warn",
      "no-redeclare": "off",
      "react/jsx-no-duplicate-props": ["warn", { "ignoreCase": false }],
      "no-unused-expressions": "off"
  }
};
```
---

# #5. 한글 폰트 사용(1)

### src/index.css body에 **font-family** 추가 

```
body {
  margin: 0;
  font-family: 'Apple SD Gothic Neo', 'Noto Sans KR', 'NanumBarunGothic', '맑은 고딕',
    'Malgun Gothic', '굴림', 'Gulim', '돋움', 'Dotum', 'Helvetica Neue',
    'Helvetica', Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
```
---

# #5. 한글 폰트 사용(2)

### public/index.html 에 webfont 추가

```
<link href="https://fonts.googleapis.com/css?family=Noto+Sans+KR&display=swap" rel="stylesheet">
```

---

# #6 Template Material UI


## [Material UI Template](https://material-ui.com/getting-started/templates/)

---
