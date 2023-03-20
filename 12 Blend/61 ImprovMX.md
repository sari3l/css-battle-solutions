# 61 ImprovMX

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16776568981704/16776569132212.png)

## done 

简直丑陋

```html
<i>
<style>
  *, *::after, i::before {
    content: '';
    position: absolute;
    margin: var(--m);
    padding: var(--p);
    border: var(--t);
    background: var(--b, #191919);
    border: 10px solid #5DBCF9;
  }  
  html{
    --m: 66 175;
    --p: 10 15;
  }
  html::after {
    --m: 45 -5;
    --p: 26.5 0;
    border: 5px solid #5DBCF9;
  }
  body {
    --m: 10 -50;
    --p: 25 40;
    border-bottom: 0;
  }
  i::after {
    --m: -83 -75;
    --p: 12 40;
    transform: rotate(-30deg);
    border-width: 10px 0 0 10px;
  }
  i::before {
     --m: -83 -15;
    --p: 12 40;
    transform: rotate(30deg);
    border-width: 10px 10px 0;
  }
  body::after {
    --b: #5DBCF9;
    --m: 63 -110;
    --p: 5 100;
    border: 10px solid #191919;
  }
  i {
    --m: 93 -55;
    --p: 0 50;
    --b: transparent;
    border-width:5px;
  }
</style>
```