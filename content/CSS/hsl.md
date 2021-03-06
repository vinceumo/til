---
type: post
showtableofcontents: true
title: hsl() & hsla()
date: 2018-08-17T08:42:00.000+00:00
category: CSS
post_type: post
showtableofcontents: true
canonical: ''

---
`hsl()` defines color using the HSL(A) model. It stands for hue, saturation and lightness.

- `H`: Hue, this is a degree on the color wheel from 0 to 360. Red is a 0, yellow at 60, green at 120, cyan at 180, blue at 240 and magenta at 300.
- `S`: Saturation, It is set from 0% to 100%, where 0% is a shade of grey and 100% is the full color vivid color.
- `L`: Lightness, It is set from 0% to 100%, where 0% is black and 100% is white. Above 50% you add white to your color, bellow 50% you add black to your color.
- `A`: Alpha (optional), the alpha channel set the opacity of the color, 0 is fully transparent and 1 is fully opaque.

```
color: hsl(`hue from 0 to 360`, `saturation from 0% to 100%`, `lightness from 0% to 100%` [`Alpha from 0% to1 100%`])
```

![HSL color wheel]({{< static "images/hsl.jpg" >}})

## `H` Hue - test

<p data-height="500" data-theme-id="dark" data-slug-hash="zLgqZb" data-default-tab="result" data-user="vinceumo" data-pen-title="hsl() test - Hue" class="codepen">See the Pen <a href="https://codepen.io/vinceumo/pen/zLgqZb/">hsl() test - Hue</a> by Vincent Humeau (<a href="https://codepen.io/vinceumo">@vinceumo</a>) on <a href="https://codepen.io">CodePen</a>.</p>
<script async src="https://static.codepen.io/assets/embed/ei.js"></script>

## `S` Saturation - test

<p data-height="500" data-theme-id="dark" data-slug-hash="QBeNGa" data-default-tab="result" data-user="vinceumo" data-pen-title="hsl() test - Saturation" class="codepen">See the Pen <a href="https://codepen.io/vinceumo/pen/QBeNGa/">hsl() test - Saturation</a> by Vincent Humeau (<a href="https://codepen.io/vinceumo">@vinceumo</a>) on <a href="https://codepen.io">CodePen</a>.</p>
<script async src="https://static.codepen.io/assets/embed/ei.js"></script>

## `L` Lightness - test

<p data-height="500" data-theme-id="dark" data-slug-hash="XBvdJx" data-default-tab="result" data-user="vinceumo" data-pen-title="hsl() test - Lighteness" class="codepen">See the Pen <a href="https://codepen.io/vinceumo/pen/XBvdJx/">hsl() test - Lightness</a> by Vincent Humeau (<a href="https://codepen.io/vinceumo">@vinceumo</a>) on <a href="https://codepen.io">CodePen</a>.</p>
<script async src="https://static.codepen.io/assets/embed/ei.js"></script>

## Resources

- [color - hsl and hsla - MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/color_value)
- [CSS hsl() Function - Quackit](https://www.quackit.com/css/color/values/css_hsl_function.cfm)
- [hsl() - codrops](https://tympanus.net/codrops/css_reference/hsl/)
- [On Switching from HEX & RGB to HSL - Sara Soueidan](https://www.sarasoueidan.com/blog/hex-rgb-to-hsl/)