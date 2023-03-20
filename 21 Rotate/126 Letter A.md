# 126 Letter A

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16770716386197/16770716511984.jpg)

## 分析

rotate 翻转多香，但是新学到了一个拉伸`skew`，延伸的有`skewX`、`skewY`，具体算法查看参考资料

```html
<div></div>
<style>
  * {
    background: #62306D;
  }
  body::before, div::after {
    content: ''; 
    width: 43px;
    height: 140px;
    position: absolute;
    margin: 72px 200px;
    background: #C5B732;
    transform: skewX(20deg);
  }
  div::after {
    margin: 72px 140px;
    background: #FEF9CA;
    transform: skewX(-20deg);
  }
  div::before,body::after {
    content: ''; 
    width: 52px;
    height: 50px;
    margin: 162px 190px;
    position: absolute;
    background: #AA445F;
    transform: skewX(40deg);
  }
  body::after {
    margin: 162px 142px;
    background: #E38F66;
    transform: skewX(-40deg);
  }
</style>
```

但是吧，看到了一个利用background + linear-gradient的操作，就感觉自己好傻

## done

但是这种方法做题还行，对于生产页面还是很垃圾的效果

```html
<style>
  html {
    border: 80px solid #62306D;
    background: linear-gradient(130deg, #0000 74q, #E38F66 0 116q, #0000 0) 0 95q no-repeat,
      linear-gradient(50deg, #0000 174q, #AA445F 0 216q, #0000 0) 0 95q no-repeat,
      linear-gradient(110deg, #0000 94q, #FEF9CA 0 136q, #0000 0) no-repeat,
      #62306D linear-gradient(70deg, #0000 153q, #c5b732 0 196q, #0000 0) no-repeat
  }
</style>
```


## 参考资料

1. [skew()](https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/skew)