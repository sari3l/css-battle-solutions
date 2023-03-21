# 11 Eye of Sauron

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16772306592618/16772306683890.png)

## 分析

怎么想都要用完两个伪元素，中间用shadow或者graident都可以

## done

```html
<div></div>
<style>
  body {
    background: #191210;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  div{
    width: 140;
    height: 140;
    border-radius: 50%;
    background: radial-gradient(#84271C 25px, #191210 0, 50px, #ECA03D 50px);
  }
  div::before, div::after {
    content: '';
    position:absolute;
    width: 60;
    height: 60;
    left: 50;
    top: 100;
    border: 20px solid;
    border-color: transparent transparent #ECA03D #ECA03D;
    border-radius: 50%;
    transform: rotate(-45deg);
  }
  div::after {
    left: 250;
    transform: rotate(135deg);
  }
</style>
```