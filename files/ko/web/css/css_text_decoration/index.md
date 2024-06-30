---
title: CSS Text Decoration
slug: Web/CSS/CSS_text_decoration

---

{{CSSRef}}

**CSS Text Decoration**은 밑줄, 텍스트 그림자 및 강조 표시 등 텍스트 장식에 관련된 기능을 정의하는 CSS 모듈입니다.

## 참고서

### 속성

- {{cssxref("letter-spacing")}}
- {{cssxref("text-align")}}
- {{cssxref("text-decoration")}}
- {{cssxref("text-decoration-color")}}
- {{cssxref("text-decoration-line")}}
- {{cssxref("text-decoration-style")}}
- {{cssxref("text-emphasis")}}
- {{cssxref("text-emphasis-color")}}
- {{cssxref("text-emphasis-position")}}
- {{cssxref("text-emphasis-style")}}
- {{cssxref("text-indent")}}
- {{cssxref("text-rendering")}}
- {{cssxref("text-shadow")}}
- {{cssxref("text-transform")}}
- {{cssxref("white-space")}}
- {{cssxref("word-spacing")}}


## Examples

```css
.under {
  text-decoration: underline red;
}

.over {
  text-decoration: wavy overline lime;
}

.line {
  text-decoration: line-through;
}

.plain {
  text-decoration: none;
}

.underover {
  text-decoration: dashed underline overline;
}

.thick {
  text-decoration: solid underline purple 4px;
}

.blink {
  text-decoration: blink;
}
```

```html
<p class="under">This text has a line underneath it.</p>
<p class="over">This text has a line over it.</p>
<p class="line">This text has a line going through it.</p>
<p>
  This <a class="plain" href="#">link will not be underlined</a>, as links
  generally are by default. Be careful when removing the text decoration on
  anchors since users often depend on the underline to denote hyperlinks.
</p>
<p class="underover">This text has lines above <em>and</em> below it.</p>
<p class="thick">
  This text has a really thick purple underline in supporting browsers.
</p>
<p class="blink">
  This text might blink for you, depending on the browser you use.
</p>
```

{{EmbedLiveSample('Examples','auto','320')}}

## Specifications

{{Specifications}}

