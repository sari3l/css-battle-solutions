# 28 Cups & Balls 

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16774155353213/16774155447234.png)

## done

```html
<div></div>
<style>
  * {
    background: #1A4341;
  }
  div {
    margin: 90 62;
    width: 50;
    height: 50;
    border-radius: 50%;
    background: #998235;
    box-shadow: 70px 70px #998235, 210px 0 #F3AC3C, 140px 70px #F3AC3C;
  }
  div::before, div::after  {
    content: '';
    position: absolute;
    width: 50;
    height: 50;
    border-radius: 0 0 50% 50%;
    background: #F3AC3C;
  }
  div::before {
    margin: 70 0;
    box-shadow: 210px 0 #998235;
  }
  div::after {
    border-radius: 50% 50% 0 0;
    margin: 0 70;
    box-shadow: 70px 0 #998235;
  }
</style>
```