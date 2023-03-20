# 41 Fox Head

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16774030453543/16774030515245.png)

## 分析

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16774030453543/16774030984521.jpg)

两个元素，然后镜像一下

## done

```html
<div></div>
<style>
  * {
    background:#293462;
  }  
  div {
    position: absolute;
    width: 50;
    height: 150;
    top:180;
    left: 150;
    background: #293462;
    box-shadow: 0 -100px #FE5F55;
    border-radius: 0 40px 0 0;
    -webkit-box-reflect: right;
  }
  div::before {
    position: absolute;
    content: '';
    width: 30;
    height: 30;
    background: #293462;
    left: 15;
    top: -40;
    border-radius: 50%
  }
</style>
```