# 100 CSSBattle

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16784165859051/16784165926748.png)

## 分析

下面的`polygen path`要理解好

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16784165859051/16784207129991.jpg)

## done

```html
<u><i><r><m>
<style>
  * {
    position: absolute;
    margin: var(--m);
    padding: var(--p);
    border-radius: var(--r);
    background: var(--b, #14313E);
  }
  u {
    --p: 75 20;
    --b: #FFDF00;
    --r: 20px 0 0 20px;
    --m: 75 63;
    -webkit-box-reflect: right 194px;
  }
  i {
    --p: 50 10;
    --b: #14313E;
    --r: 10px 0 0 10px;
    --m: -50 5;
  }
  r {
    --b: #FFDF00;
    --p: 20 5;
    --r: 5px 0 0 5px;
    --m: -20 -45;
  }
  m {
    --r: 0;
    --p: 105 40;
    --m: -110 103;
    transform: rotate(-45deg);
    --b: linear-gradient(#0000 150.5px, #FFDF00 150.5px 170.5px, #0000 0),
      linear-gradient(90deg, #0000 30px, #FFDF00 0 49.5px, #0000 0) no-repeat 0 170px,
      linear-gradient(90deg, #0000 15px, #14313E 0 25px, #FFDF00 0 54.5px, #14313E 0 65px, #0000 0) no-repeat 0 -58px;
    clip-path: polygon(50% 0, 100% 20%, 100% 85%, 57% 100%, 43% 100%, 0 85%, 0 20%)
  }
</style>
```