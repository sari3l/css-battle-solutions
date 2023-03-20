# 132 Letter S

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16771395866119/16771395999590.jpg)

## 分析

...没得说，就是干，四个大块用阴影，中间横为一部分，两个竖是一部份

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16771395866119/16772289504714.jpg)

## done

```html
<div></div>
<style>
  * {
    background: #4F77FF;
  }
  div {
    margin: 70 72;
    border: 25px solid;
    border-radius: 10px;
    color: #FFFFFF;
    box-shadow: 22q -22q #1038BF,
      0 116q #FFFFFF,
      -22q 138q #1038BF;
    position: relative;
  }
  div::before {
    content: '';
    position: absolute;
    margin: 45 -25;
    width: 240px;
    height: 20px;
    border-radius: 0 10px 0 10px;
    background: #FFFFFF;
  }
  div::after {
    content: '';
    position: absolute;
    margin: 15 -25;
    width: 20px;
    height: 40px;
    border-radius: 0 10px 0 10px;
    background: #FFFFFF;
    box-shadow: 220px 40px #FFF;
  }
  ```