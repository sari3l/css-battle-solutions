# 129 Letter B

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16771309097707/16771309206637.jpg)

## 分析

怎么看都是box-shadow，这里有个坑点，如果取半而设置高度为70，右下角的弧度是直接调不出来的，实际上是截断的弧度

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16771309097707/16771318882792.jpg)


## done

```html
<div></div>
<style>
  * {
    background: #6592CF;
  }  
  div {
    width: 100;
    height: 80;
    background: #060F55;
    margin: 80 102;
    border-radius: 0 40px 40px 0;
    box-shadow: 0 60px #060F55,40px 0px #2E3B9F,40px 60px #2E3B9F,80px 0px #515DBD,80px 60px #515DBD;
  }
</style>
```