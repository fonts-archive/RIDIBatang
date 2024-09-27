# 리디바탕

[배포처 바로가기](https://ridicorp.com/ridibatang/)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `RIDI Batang`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/RIDIBatang/RIDIBatang.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/RIDIBatang/RIDIBatang.css');
```

### CSS `@font-face`

```css
@font-face {
    font-family: 'RIDI Batang';
    font-weight: normal;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/RIDIBatang/RIDIBatang.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/RIDIBatang/RIDIBatang.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/RIDIBatang/RIDIBatang.otf') format('opentype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/RIDIBatang/subsets/RIDIBatang-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/RIDIBatang/subsets/RIDIBatang-dynamic-subset.css');
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.

```css
font-family: "RIDI Batang", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
리디바탕 글꼴은 개인 및 기업 사용자를 포함한 모든 사용자에게 무료로 제공되며 자유롭게 수정하고 재배포하실 수 있습니다. 
단, 글꼴 자체를 유료로 판매하는 것은 금지하며, 리디바탕 글꼴은 본 저작권 안내와 라이선스 전문을 포함해서 다른 소프트웨어와 번들하거나 재배포 또는 판매가 가능합니다. 
라이선스 전문을 포함하기 어려울 경우, 리디바탕 글꼴의 출처 표기를 권장합니다. 예) 이 페이지는 리디주식회사에서 제공한 리디바탕 글꼴이 사용되어 있습니다. 
This Font Software is licensed under the SIL Open Font License, Version 1.1. 
리디바탕의 저작권은 리디주식회사가 소유하고 있습니다.
```
