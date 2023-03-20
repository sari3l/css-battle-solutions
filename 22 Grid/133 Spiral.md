# 133 Spiral

手法有很多，其中一个比较厉害的，虽然我是实在不懂161个字符就能画出这个的是什么神仙

- [CSSBattle.dev - #133 (Spiral)](https://vishalsingh.hashnode.dev/cssbattledev-133-spiral)

## 分析

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16708981086202/16708985128884.jpg)

首先抛去两端的半圆结点，实际可认为是四个半圆，半圆是很好画的

## Do it

文中作者是通过勾画一个小半圆，再通过box-shadow扩展一层透明➕一层大圈

```css
width: 40px;
height: 40px;
border: 20px solid #d86f45;
border-radius: 50%;
box-shadow: 0px 0px 0px 20px #f5d6b4, 0px 0px 0px 40px #d86f45;
```

再通过计算截取一半的圆

```css
margin: 110px auto;
```

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16708981086202/16709008949067.jpg)

再往上推下面的半圆，使其漏出下半部分，同时将其放大一些，并设置其左边margin，使其偏移

```css
height: 80px;
width: 80px;
margin: -60px 120px;
```

对于最后的结点，在任意半区半圆前后绘制即可

```css
content: "";
position: absolute;
width: 20px;
height: 20px;
background: #d86f45;
border-radius: 50%;
margin: 8px -20px;
box-shadow: -80px 0 0 #d86f45;
```

## Done

```html
<!DOCTYPE html>
<html lang="en">
  <body>
    <div class="root">
      <div class="upper">
        <div class="top"></div>
      </div>
      <div class="lower">
        <div class="bottom"></div>
      </div>
    </div>
    <style>
      * {
        margin: 0;
        background: #f5d6b4;
      }
      .root {
        width: 400px;
        height: 300px;
        display: flex;
        flex-direction: column;
      }
      .upper,
      .lower {
        height: 100%;
        overflow: hidden;
      }
      .top,
      .bottom {
        width: 40px;
        height: 40px;
        margin: 110px auto;
        border: 20px solid #d86f45;
        border-radius: 50%;
        box-shadow: 0px 0px 0px 20px #f5d6b4, 0px 0px 0px 40px #d86f45;
      }
      .bottom {
        height: 80px;
        width: 80px;
        margin: -60px 120px;
      }
      .top::before {
        content: "";
        position: absolute;
        width: 20px;
        height: 20px;
        background: #d86f45;
        border-radius: 50%;
        margin: 8px -20px;
        box-shadow: -80px 0 0 #d86f45;
      }
    </style>
  </body>
</html>
```

[![Edit # 133](https://codesandbox.io/static/img/play-codesandbox.svg)](https://codesandbox.io/s/133-lyj1s7?fontsize=14&hidenavigation=1&theme=dark)
