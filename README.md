# 도스샘물

[배포처 바로가기](https://github.com/hurss/fonts)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `DOSSaemmul`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/DOSSaemmul/DOSSaemmul.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/DOSSaemmul/DOSSaemmul.css');
```

### CSS `@font-face`

```css
@font-face {
    font-family: 'DOSSaemmul';
    font-weight: normal;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/DOSSaemmul/DOSSaemmul.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/DOSSaemmul/DOSSaemmul.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/DOSSaemmul/DOSSaemmul.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/DOSSaemmul/DOSSaemmul.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/DOSSaemmul/subsets/DOSSaemmul-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/DOSSaemmul/subsets/DOSSaemmul-dynamic-subset.css');
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.



```css
font-family: "DOSSaemmul", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
FAQ 
1. 상업적 이용 문의 (라이선스 관련) 현재 MIT 라이선스로 배포하고 있습니다. 
2. 영리목적 사용 (메신저 이모티콘 등) 가능합니다. 대신 부가 설명에 ‘글꼴(폰트)로 도스샘물체(leedheo 제작)를 사용하였습니다’ 형태로 기재하시면 되겠습니다. 
3. 폰트 출처 및 이용 명시 등에 관하여 폰트 원출처는 https://github.com/hurss/fonts 입니다. 눈누에 갱신 관련 연락을 넣어 보았으나 닉네임에 사이트 링크가 되지 않은 관계로, 출처 표시를 해 주시면 감사하겠습니다.
```
