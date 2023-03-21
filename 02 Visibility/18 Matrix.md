# 18 Matrix

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16772246362074/16772246429695.png)

## 分析

直观的看用grid会很快，但是都是重复的内容，box-shadow也可以

## done

```html
<div></div>
<style>
  body {
    background: #5C434C;
    margin: 10px;
  }
  div {
    width: 80px;
    height: 80px;
    background: #F09462;
    border-radius: 100% 0 0;
    box-shadow: 200px 0 #F09462, 100px 100px #F09462, 300px 100px #F09462, 0 200px #F09462, 200px 200px #F09462, 100px 0 #F5D6B4, 300px 0 #F5D6B4, 0 100px #F5D6B4, 200px 100px #F5D6B4, 100px 200px #F5D6B4, 300px 200px#F5D6B4;
  }
</style>
```