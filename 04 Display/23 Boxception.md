# 23 Boxception

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16774128788259/16774128882576.png)

## 分析

原本觉得就是一个方块各种shadow，结果又被教育

```html
<div></div>
<style>
  * {
    background: #F3AC3C;
  }
  div {
  position: absolute;
    width: 100;
    height: 100;
    top: 50;
    left: 100;
    background: #1A4341;
    box-shadow: 100px 0 #1A4341, 100px 100px #1A4341, -25px 125px 0 -25px #998235, -25px 75px 0 -25px #998235, 25px 75px 0 -25px #998235;
</style>
```

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16774128788259/16774132318172.jpg)

直接一个块向外shadow!

## done

```html
†
```