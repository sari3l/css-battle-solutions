# 135 Spikes

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16770379631139/16770517184412.jpg)

## 分析

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16770379631139/16770447815145.jpg)

为了简便，可以认为是胶囊型1做4个shadow，然后放置一个底色转45deg的方块并对称，通过减法实现

加法呢？能不能通过以左上角的内容对称两次？可惜平台不让svg

```css
div {
  width: 100px;
  height: 40px;
  background-color: red;
  clip-path: path("M 0 0 l 50 0 A 20 20 0 0 1 50 40 h -10 z");
}
```

## Done

```html
<div></div>
<style>
  * {
    background:#E3516E;
  }
  div {
    position: relative;
    margin: 100px 82px;
    width: 100px;
    height: 40px;
    border-radius: 20px;
    background: #D9D9D9;
    box-shadow: 120px 0px #D9D9D9, 0 60px #D9D9D9, 120px 60px #D9D9D9;
  }
  div::before, div::after {
    position: absolute;
    content: '';
    left: -42px;
    width: 100px;
    height: 100px;
    rotate: 45deg;
    background: #E3516E;
  }
  div::after {
    left: 162px;
  }
</style>
```

