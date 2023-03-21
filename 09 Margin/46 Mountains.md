# 46 Mountains

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16773937743889/16773952035568.png)


## 分析

主要是border + hidden，要理解清border产生的模式

## done 

```html
<div></div>
<style>
  * {
    background: #293462;
  }
  div {
    position: absolute;
    top:50;
    left:100;
    width: 200;
    height: 200;
    background: #FFF1C1;
    border-radius: 50%;
    overflow: hidden;
  }
  div::before, div::after {
    content: '';
    position: absolute;
    border: 145px solid;
    border-color: transparent transparent #FE5F55;
    top: -86;
    left: -3.5;
  }
  div::after {
    top: -16;
    left: -115.5;
  }
</style>
```