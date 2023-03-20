# 27 Lock Up

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16774152418934/16774152516071.png)

## 分析

shadow和border是互不影响的，所以一个圆搞定 

## done

```html
<div></div>
<style>
  * {
    background: #E38F66;
  }
  div {
    margin: 80 122;
    width: 80;
    height: 80;
    border-radius: 50%;
    background: #AA445F;
    border: 30px solid;
    border-color: #F7EC7D transparent;
    transform: rotate(45deg);
    box-shadow: 0 0 0 30px #AA445F;
  }
</style>
```