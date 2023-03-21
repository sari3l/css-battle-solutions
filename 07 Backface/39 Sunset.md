# 39 Sunset

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16774016755013/16774016830553.png)

## done

很奇怪，body不能用`*`代替，否则是99.9%

```html
<div></div>
<style>
  body {
    background: #1A4341;
  }  
  div {
    position: absolute;
    left: 75;
    top: 25;
    width: 250;
    height: 250;
    border-radius: 50%;
    overflow: hidden;
  }
  div::before {
    content: '';
    position: absolute;
    width: 200;
    height: 200;
    top: 25;
    left: 25;
    background: #998235;
    border-radius: 50%;
  }
  div::after {
    content: '';
    position: absolute;
    width: 250;
    height: 20;
    top: 55;
    background: #1A4341;
    box-shadow: 0 40px #1A4341, 0 80px #1A4341, 0 120px #1A4341, 0 20px #F3AC3C, 0 60px #F3AC3C, 0 100px #F3AC3C;
  }
</style>
```