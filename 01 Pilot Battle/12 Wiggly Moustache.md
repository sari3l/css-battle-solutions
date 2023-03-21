# 12 Wiggly Moustache

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16772307815813/16772308188636.png)

## 分析

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16772307815813/16772316121743.jpg)

感觉和`#4`很像，以为就是端点加个圆点，但是吧，一个它是内凹的，二是我又忘记**shadow是没有border的**

## done

最后通过before的shadow来构造两边的原型，半弧从左到右分别是`div -> div::after -> div::before`，这里却出了个问题，before的shadow盖住了after的border甚至是after本身，这个是不应该的（看延伸）

```html
<div></div>
<style>
  * {
    background: #F5D6B4;
  }
  div, div::before, div::after {
    content: '';
    position: absolute;
    top: 100;
    left: 70;
    width: 60;
    height: 60;
    background: #F5D6B4;
    border: 20px solid;
    border-color: transparent transparent #D86F45 #D86F45;
    border-radius: 50%;
    transform: rotate(-45deg);
    mix-blend-mode: darken;
  }
  div::before {
    top: 36.5;
    left: 35.5;
    transform: rotate(180deg);  
    box-shadow:-85px -85px 0 -40px #D86F45, 85px 85px 0 -40px #D86F45;
  } 
   div::after {
    top: 93;
    left: 93;
    transform: rotate(0deg);
  }
</style>
```

## 延伸

这里出现了很有意思的问题，从元素上来说高度

> border和其元素在一层
> ::after > ::after.shadow > ::before > ::before.shadow > 原始元素 > 原始元素.shadow

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16772307815813/16773838485445.jpg)
