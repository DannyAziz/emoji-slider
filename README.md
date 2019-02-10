# emoji-slider
A slider control which uses an emoji as the thumb.

This is built as a web component, so it's usable anywhere with HTML.

[View live demo.](https://pshihn.github.io/emoji-slider/demo/)

![Emoji Slider](https://i.imgur.com/hzzSolP.png)

## Usage

Get the compoent 

```
npm install --save emoji-slider
```

Import in a JavaScript module:

``` javascript
import 'emoji-slider';
```

Or in an HTML page:
```html
<script type="module" src="./node_module/emoji-slider/bin/emoji-slider.js"></script>
```

And then use it in HTML

```
<emoji-slider emoji="😍"></emoji-slider>
```

More about using web components [here](https://lit-element.polymer-project.org/guide/use).

## Properties

**value:** The numeric value of the slider between 0 and 1.

**emoji:** The emoji character to use in the thumb of the slider. If not set, a circular thumb is used.

## Styling
The slider bar color be styles using CSS properties. For example,

```css
emoji-slider {
  --emoji-slider-bar-color: red;
}
```

## License
[MIT License](https://github.com/pshihn/emoji-slider/blob/master/LICENSE) (c) [Preet Shihn](https://twitter.com/preetster)

