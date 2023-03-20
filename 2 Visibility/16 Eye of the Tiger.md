# 16 Eye of the Tiger

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16772093083795/16772093176306.png)

## 分析

使用radial-gradient做环

## done

```html
<div></div>
<style>
  * {
    background: #0B2429;
  }
  div,div::after {
    position: absolute;
    top: 16.5%;
    left: 25%;
    width: 200;
    height: 200;
    transform: rotate(45deg);
    border-radius: 50% 0 50%;
    background: #998235;
  }
  div::after{
    content: '';
    top:0%;
    left:0%;
    border-radius:50%;
    background: radial-gradient(#0B2429 25px, #F3AC3C 0, 70px, #0B2429 0, 90px, #998235 0);
  }
</style>
```