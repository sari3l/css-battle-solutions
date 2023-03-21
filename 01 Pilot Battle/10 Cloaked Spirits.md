# 10 Cloaked Spirits

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16772302519604/16772302634071.png)

## 分析

两个主体

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16772302519604/16772303221642.jpg)

## done

```html
<div></div>
<style>
  * {
    background: #62306D;
  }
  div {
    position: absolute;
    left: 50;
    top: 200;
    width: 100;
    height: 200;
    background: #F7EC7D;
    box-shadow: 100px -100px #F7EC7D, 200px 0 #F7EC7D;
  }
  div::after {
    content: '';
    position: absolute;
    width: 60;
    height: 60;
    border-radius: 50%;
    background: #E38F66;
    left: 20;
    top: -30;
    box-shadow: 0 0 0 20px #AA445F, 100px -100px #AA445F, 100px -100px 0 20px #E38F66, 200px 0 #E38F66, 200px 0 0 20px #AA445F;
  }
</style>
```