# 62 Sunset

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16776606097830/16776606163387.png)

## done

```html
<style>
  *, *::after {
    content: '';
    position: absolute;
    margin: var(--m);
    padding: var(--p);
    border-radius: var(--r, 50%);
    background: var(--b, #191919);
    overflow:hidden;
  }
  body {
    --p: 100 75;
    --m: 50 125;
    --r: 75px 75px 20px 20px;
    --b: #F2AD43;
  }
  body::after {
    --r: 50%;
    --p: 100;
    --m: 0 -25;
    --b: #824B20;
    box-shadow: -150px 0 #E08027, -75px -80px 0 -70px #FFF58F;
  }
</style>
```