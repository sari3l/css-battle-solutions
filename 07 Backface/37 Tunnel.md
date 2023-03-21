# 37 Tunnel

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16774013892580/16774013966370.png)

## 分析

一眼看去，需要rotate只能上伪元素

## done

```html
<div></div>
<style>
  * {
    background: #6592CF;
  }  
  div {
    position: absolute;
    width: 250;
    height: 250;
    top: 25;
    left: 75;
    background: #243D83;
  }
  div::before, div::after{
    content: '';
    position: absolute;
    width: 150;
    height: 150;
    background: #6592CF;
    top: 50;
    left: 50;
    transform: rotate(15deg);
  }
  div::after {
    width: 75;
    height:75;
    top: 87.5;
    left: 87.5;
    transform: rotate(30deg);
    background: #243D83;
  }
</style>
```