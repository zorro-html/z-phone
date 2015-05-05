# `<z-phone>`

Phone shell element, which could contains content to preview like in a smart phone

## Attributes

- `innerwidth`: adjust the size the adapt the width of content in the phone cell
- `size`: JSON data to record `width`, `height`, `top` padding, `bottom` padding and `side` padding of the phone cell
- `bgimg`: image url of the phone, which is appropriate to the `size`

## Examples

```
<z-phone innerwidth="240">
  <div style="background: silver; height: 800px;">Hello World</div>
</z-phone>

<z-phone size="{'width': 374, 'height': 777, 'top': 102, 'bottom': 102, 'side': 27}" bgimg="iphone.png" innerwidth="240">
    <div style="background: silver; height: 800px;">Hello World</div>
</z-phone>
```
