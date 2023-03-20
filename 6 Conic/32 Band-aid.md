# 32 Band-aid

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16771570804986/16771570940353.jpg)

虽然我隐约觉得这个颜色肯定有问题，但是还是头铁用了渐变

```html
<div></div><div b></div>
<style>
  div {
    position: absolute;
    top: 125px;
    left: 25%;
    width: 200px;
    height: 50px;
    transform: rotate(45deg);
    background: #F3AC3C;
  }
  div[b] {
    transform: rotate(-45deg);
    background: linear-gradient(to right, #A3A368 37.5%, #FBE18C 37.5%, 62.5%, #A3A368 62.5% );
  }
</style>
```

## done 

被大佬吊打每一天，使用`mix-blend-mode`直接算出中间色块

${\displaystyle f(a,b)=1-(1-a)(1-b)}$

```html
<div></div><div b></div>
<style>
  * {
    mix-blend-mode:screen;
  }
  div {
    position: absolute;
    top: 125px;
    left: 25%;
    width: 200px;
    height: 50px;
    transform: rotate(45deg);
    background: #F3AC3C;
  }
  div[b] {
    transform: rotate(-45deg);
    background: #A3A368;
  }
</style>
```