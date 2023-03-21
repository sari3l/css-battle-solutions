# 31 Equals

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16771564463385/16771564626441.jpg)

## 分析

原本觉得伪类多简单啊

```html
<div></div>
<style>
  * {
    background: #AA445F;
  }
  div::before, div::after {
    content: '';
    position: absolute;
    width: 100;
    height: 200;
    top: 50;
    left: 75;
    border-radius: 200px 0 0 200px;
    background: #F7EC7D;
  }
  div::after {
    transform: rotate(180deg);
    left: 225px;
    background: #E38F66;
  }
</style>
```

然后被大佬一顿毒打，忘记了渐变，有时候就是差这么一点

## done

```html
<div></div>
<style>
  * {
    background: #AA445F;
  }
  div {
    position: absolute;
    top: 50;
    left: 75;
    width: 250px;
    height: 200px;
    background: linear-gradient(to right, #F7EC7D 100px, #AA445F 100px, 150px, #E38F66 120px);
    border-radius: 200px;
  }
</style>
```
