# 25 Blossom

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16774138166333/16774138229349.png)

## 分析

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16774138166333/16774138965895.jpg)

拆解看，其实就是两个部分，对于侧面可放多个来实现直边，但这种侧边重叠少的话就会很明显

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16774138166333/16774144266067.jpg)

## done 

```html
<div></div>
<style>
  * {
    background: #998235;
  }
  div, div::after {
    margin: 60 102;
    width: 80;
    height: 60;
    background: #1A4341;
  }
  div{
    border-radius: 0 50px;
    box-shadow: 0 15px #1A4341,0 25px #1A4341, 0 40px #1A4341, 0 120px #F3AC3C;
  }
  div::after {
    content: '';
    position: absolute;
    left: 108;
    top: 80;
    border-radius: 50px 0;
    box-shadow: 0 15px #1A4341,0 25px #1A4341, 0 40px #1A4341, 0 -80px #F3AC3C;
  }
</style>
```