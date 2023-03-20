# 50 Use Hand Sanitizer

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16774884336002/16774884439714.png)

## 分析

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16774884336002/16775000727040.jpg)

怎么看都需要六个部分

## done

```html
<img><i><b><o><t>
<style>
  * {
    background: #1A4341
  }
  * * {
    position: absolute;
    padding: var(--p, 0);
    margin: var(--m, 0);
    border-radius: var(--r, 20px);
    background: var(--b, #F3AC3C);
  }
  img {
    --p: 70 50;
    --m: 110 150;
    --b: linear-gradient(#F3AC3C 40%, #998235 0)
  }
  i {
    --p: 30 25;
    --r: 10px;
    --m: 90 175;
  }
  b{
    --p: 10 75;
    --m: -70 -50;
  }
  o {
    --p: 20 10;
    --m: -10 55;
    box-shadow: -90px 10px #F3AC3C;
  }
  t{
    --p: 10;
    --m: 30 -10;
    --b: #998235;
    box-shadow: 0 30px #998235, -65px 55px 0 15px #F3AC3C, -115px 55px 0 15px #998235;
  }
</style>
```