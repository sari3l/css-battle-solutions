# 19 Cube

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16774163833622/16774163956734.png)

## done

```html
<div></div>
<style>
  * {
    background: #0B2429;
  }
  div {
    margin: 135 142;
    transform: rotate(45deg);
    width: 100;
    height: 101;
    background: #F3AC3C;
  }
  div::before, div::after {
    content: '';
    position: absolute;
    width: 71;
    height: 71;
    margin: -10 -60;
    background: #998235;
  }
  div::before {
     transform: rotate(45deg) skewX(45deg);
  }
  div::after {
    margin: -60 -10;
    background: #1A4341;
    transform: rotate(45deg) skewX(-45deg);
  }
</style>
```