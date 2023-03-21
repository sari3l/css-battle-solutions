# 33 Birdie

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16773979302744/16773979395937.png)

## done

```html
<div></div>
<style>
  * {
    background: #1A4341;
  }
  div {
    position: absolute;
    top: 75;
    left: 125;
    width: 75;
    height: 150;
    border-radius: 75px 0 0 75px;
    background: #998235;
  }
  div::before {
    content: '';
    position: absolute;
    width: 30;
    height: 30;
    background: #0B2429;
    border-radius: 50%;
    top: 30;
    left: 30;
  }
  div::after {
    content: '';
    position: absolute;
    width: 100;
    height: 100;
    background: #F3AC3C;
    border-radius: 0 100% 0 0;
    top: -25;
    left: 75;
  }
</style>
```