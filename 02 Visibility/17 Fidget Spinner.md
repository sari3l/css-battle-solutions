# 17 Fidget Spinner

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16772103337975/16772103419050.png)

## 分析

通过三个大圆来控制边缘过渡，再让两个伪类border来构建隔离

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16772103337975/16772244507179.jpg)


## done

```html
<div></div>
<style>
  * {
    background: #09042A;
  }
  div {
    position: absolute;
    top: 36.5%;
    left:25%;
    width: 80;
    height: 80;
    background: #E78481;
    box-shadow: 60px 0 #E78481, 120px 0 #E78481;
    border-radius: 40px;
  }
  div::before, div::after {
    content: '';
    position: inherit;
    top: -52.5;
    left: 60;
    width: 60;
    height: 60;
    border-radius: 40px;
    background: #F5BB9C;
    border: 10px solid #09042A;
    box-shadow: 60px 53px 0 -10px #09042A, -60px 53px 0 -10px #09042A;
  }
  div::after{
    top: 53;
  }
</style>
```