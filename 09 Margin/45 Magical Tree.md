# 45 Magical Tree

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16773937743889/16773937872761.png)

## 分析

直接横竖的shadow因为等比例缩小，小框会缩水，只好分解成方框shadow加上中间的十字，

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16773937743889/16773939011560.jpg)

这里其实为了做横线还犯了傻，其实shadow下移就行的orz

## done

```html
<div></div>
<style>
  * {
    background: #1A4341;
  }  
  div {
    position: absolute;
    width: 90;
    height: 120;
    top: -30;
    left: 125;
    border: 30px solid #998235;
    box-shadow: 0 0 0 30px #1A4341, 0 0 0 60px #F3AC3C, 0 30px 0 60px #1A4341, 0 60px 0 60px #998235;
  }
  div::before {
    content: '';
    position: absolute;
    width: 30;
    height: 300;
    background: #F3AC3C;
    left: 30;
    top: 0;
  }
</style>
```