# 127 Letter I

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16771211684728/16771238810306.jpg)

## 分析

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16771211684728/16771239972717.jpg)

1. 蓝色为元素，绿色为其box-shadow阴影
2. 浅蓝色为独立元素，需要伪元素来做内凹图形

这里学到了一个新的属性[`-webkit-box-reflect`](https://developer.mozilla.org/en-US/docs/Web/CSS/-webkit-box-reflect)，可以很方便的做`倒影`，有三个属性分别简单认为：`方位，距离，遮罩`

## done

没啥好办法

```html
<div class='g'><div class='r'></div></div>
<style>
  * {
    background: #e3516e;
  }
  .g {
    margin: 70 142;
    width: 100;
    height: 30;
    border-radius: 20px;
    background: #FADE8B;
    position: relative;
    box-shadow: 0 130px #FADE8B;
  }
  .g::after { 
    content: '';
    margin: 0 110px;
    border-radius: 50%;
    width: 30;
    height: 30;
    position: absolute;
    background: #FADE8B;
    box-shadow: -150px 130px #FADE8B;
  }
  .r {
    margin: 10 30;
    position: absolute;
    width: 40;
    height: 120;
    background: #FADE8B;
  }
  .r::after {
    content: '';
    margin: 20 -15;
    width: 20;
    height: 100;
    border-radius: 20px;
    position: absolute;
    background: #E3516E;
    -webkit-box-reflect: right 30px;
  }
</style>
```