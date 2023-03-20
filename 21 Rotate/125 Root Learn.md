# 125 Root Learn

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16770571871306/16770572059393.jpg)

## 分析

这玩意就是折磨人的，把它拆成三块来处理

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16770571871306/16770712948534.jpg)

> 默认层级 div < div::before < div::after

按一般思维应该把原始元素设置为底部大图形，但是经过clip-path的话会限制上层的显示，所以:

- 原始元素 -> 大红框
- ::before -> polygon蓝色框
- ::after -> 小红框

## done

```html
<div></div>
<style>
  * {
    background: #EFF2F1;
  }
  div {
    margin: 60px 162px;
    position: relative;
    width: 90px;
    height: 90px;
    background: #1C1C1C;
    border-radius: 0 45px 45px 0;
  }
  div::before {
    content: '';
    position: absolute;
    margin: 0 -60px;
    width: 180px;
    height: 180px;
    background: #1C1C1C;
    clip-path: polygon(0 0,35.5% 0, 87% 89.2%, 100% 96.5%, 100% 100%, 67.5% 100%, 38.5% 50% , 33.5% 50%, 33.5% 88.5%, 44.5% 95%, 44.5% 100%, 0 100%, 0 95%, 11% 88.5%, 11% 11%, 0 5%);
  }
  div::after {
    content: '';
    position: absolute;
    margin: 15px 0;
    width: 50px;
    height: 60px;
    background: #EFF2F1;
    border-radius: 0 45px 45px 0;
  }
</style>
```