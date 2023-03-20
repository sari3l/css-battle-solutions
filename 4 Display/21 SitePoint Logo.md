# 21 SitePoint Logo

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16774116907545/16774117302731.png)

## 分析

分为两部分，然后shadow处理

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16774116907545/16774118757472.jpg)

结果两个圆角角度不一样，还是需要两个伪类处理

## done

```html
<div></div>
<style>
  * {
    background: #222;
  }
  div {
    position: absolute;
    top: 62;
    left: 165;
    width: 30;
    height: 72;
    transform: rotate(45deg);
    background: #F2994A;
    box-shadow: 100px 46px #2D9CDB;
  }
  div::before, div::after {
    content: '';
    position: absolute;
    width: 30;
    height: 80;
    background: #F2994A;
    top: 45;
    left: 25;
    border-radius: 5px 0 10px 0;
    transform: rotate(90deg);
    mix-blend-mode: lighten;
  }
  div::after {
    top: -7;
    left: 75;
    background: #2D9CDB;
    transform: rotate(-90deg);
  }
</style>
```