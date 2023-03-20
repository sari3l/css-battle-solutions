# 66 Batmicky

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16776708269845/16776708345952.png)

## done

```html
<div>
<style>
  *, div::before, div::after {
    content: '';
    position: absolute;
    margin: var(--m);
    padding: var(--p);
    border-radius: var(--r);
    background: var(--b, #191919);
  }
  div {
    --p: 15 40;
    --m: 100 160;
    --r: 0 0 10px 10px;
    box-shadow: 0 80px 0 80px #F2AD43;
  }
  div::before {
    --b: #F2AD43;
    --p: 10;
    --m: -5 -10;
    --r: 0;
  }
  div::after {
    --b: #191919;
    --p: 100;
    --r: 50%;
    --m: 45 -160;
    box-shadow: -65px -110px 0 -50px #191919, 120px 0 #191919, 185px -110px 0 -50px #191919, 50px -150px 0 -95px #F2AD43, 70px -150px 0 -95px #F2AD43;
  }
</style>  
```