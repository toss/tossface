# 토스페이스 (Tossface)

토스페이스는 토스 팀에서 디자인한 이모지 서체입니다.
디지털 환경을 고려하여 작게 보아도 명확하게 의미가 드러날 수 있도록 단순한 형태와 최소한의 묘사를 지향합니다. [Unicode v14.0](https://unicode.org/emoji/charts-14.0/emoji-released.html)의 이모지 전체를 TTF 서체로 제공하고 있습니다.

- [폰트 다운로드](https://github.com/toss/tossface/releases/latest)
- [폰트 설치 방법](https://support.apple.com/ko-kr/HT201749)

## 웹 폰트

CDN을 이용해 아래와 같이 토스페이스를 이용할 수 있습니다. 토스페이스가 사용하는 `font-family`는 `Tossface`입니다.

<!-- markdownlint-disable-next-line MD036 -->
**CSS**

```css
@import url('https://cdn.jsdelivr.net/gh/toss/tossface/dist/tossface.css');
```

<!-- markdownlint-disable-next-line MD036 -->
**HTML**

```html
<link rel="preconnect" href="https://cdn.jsdelivr.net" />
<link rel="preconnect" href="https://cdn.jsdelivr.net" crossorigin />
<link href="https://cdn.jsdelivr.net/gh/toss/tossface/dist/tossface.css" rel="stylesheet" type="text/css" />
```

<!-- markdownlint-disable-next-line MD036 -->
**사용하기**

아래와 같이 `tossface` class 속성을 가진 HTML 요소에 토스페이스 폰트를 사용할 수 있습니다.

```css
.tossface {
  font-family: Tossface;
}
```
