# 128 Letter N

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16771242908686/16771243474569.jpg)

## 分析

原本想要box-shadow但是因为叠层缘故，还是采用伪元素构造

## done

```html
<div></div>
<style>
  * {
    background: #998235;
  }
  div, div::after {
    margin: -10 217px;
    width: 40px;
    height: 232px;
    background: #0B2429;
    position: relative;
  }
  div::before {
    content: '';
    position: absolute;
    margin: 72 -46;
    transform: skewX(20deg);
    width: 42px;
    height: 160px;
    background: #FCBE5C;
  }
  div::after {
    content: '';
    position: absolute;
    margin: 72 -90 ;;
  }
</style>
```
