# 8 Forking Crazy

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16772281441153/16772283478286.png)

## 分析

其实主体就是两个结构

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16772281441153/16772284251248.jpg)

## done

```html
<div></div>
<style>
  * {
    background: #6592CF;
  }
  div {
    margin: 150 122;
    width: 140;
    height: 100;
    border-radius: 0 0 100px 100px;
    background: #060F55;
  }
  div::after {
    content: '';
    position: absolute;
    width: 20;
    height: 120;
    top: 50;
    border-radius: 20px;
    background: #060F55;
    box-shadow: 40px 0 #060F55, 80px 0 #060F55, 120px 0 #060F55,  60px 150px #060F55, 20px -10px #6592CF, 60px -10px #6592CF, 100px -10px #6592CF;
  }
</style>
```