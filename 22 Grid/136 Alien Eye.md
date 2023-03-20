# 136 Alien Eye

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16770497130280/16770517039679.jpg)

## 分析

原本想用box-shadow直接产生圆形，但是随着尺寸增大，外围越来越趋向于圆角矩形，这个问题在css也有讨论：https://github.com/w3c/csswg-drafts/issues/7103

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16770497130280/16770498570500.jpg)

```html
<div></div>
<style>
  * {
    background:#998235;
  }
  div {
    margin: 120px 172px;
    width: 60px;
    height: 60px;
    border-radius: 50%;
    background: #998235;
    box-shadow: -10px 0 0 20px #FCBE5C, 0 0 0 40px #0B2429, -10px 0 0 60px #FCBE5C;
  }
</style>
```

还是依赖伪元素来吧

## done

```html
<div class='r'></div>
<style>
  * {
    background:#998235;
  }
  .r {
    margin: 60px auto;
    position:relative;
    width: 180px;
    height: 180px;
    background: #FCBE5C;
    border-radius: 50%;
  }
  .r::after {
    position:absolute;
    left: 70px;
    top: 60px;
    content:' ';
    width: 60px;
    height: 60px;
    border-radius: 50%;
    background: #998235;
    box-shadow: -10px 0 0 20px #FCBE5C, 0 0 0 40px #0B2429;
  }
</style>
```