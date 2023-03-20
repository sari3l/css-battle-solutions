# 138 Lotus

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16770525161607/16770525229448.jpg)

## 分析

这个题目其实有点意思，第一反应是radius，但是好像不是能控制四个角获得白色形状，其实换位思考下，控制两个角100%不就是右侧暗色的了么

## done

原本这样简洁点，结果99.9%就是过不去

```html
<div class='g'></div>
<style>
  * {
    background: #926927
  }
  .g {
    margin: 120px 192px;
    width: 100px;
    height: 100px;
    background: #6D480A;
    border-radius: 100% 0;
    position: relative;
  }
  .g::before, .g::after {
    content: '';
    position: absolute;
    inset: 0px;
    rotate: -45deg;
    transform-origin: bottom left;
    border-radius: 100px 0;
    background: #FFFFFF;
  }
  .g::before {
    rotate: -90deg;
    background: #6D480A;
  }
</style>
```

简直丑陋

```html
<div></div>
<style>
  * {
    background: #926927
  }
  div {
    margin: 120px 192px;
    width: 100px;
    height: 100px;
    background: #6D480A;
    border-radius: 100% 0;
    position: relative;
  }
  div::before, div::after {
    content: '';
    position: absolute;
    width: 100px;
    height: 100px;
    rotate: -45deg;
    border-radius: 100px 0;
    background: #FFFFFF;
    left: -50px;
    top: -20px;
  }
  div::before {
    rotate: -90deg;
    background: #6D480A;
    left: -100px;
    top: 0;
  }
</style>
```