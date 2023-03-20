# 65 Max Volume

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16776638630618/16776638722560.png)

## done

```html
<div>
<style>
  *, div::before, div::after {
    content: '';
    position: absolute;
    margin: var(--m);
    padding: var(--p);
    background: var(--b, #191919);
  }
  div {
    --p: 0;
    --m: 50 0;
    border: 100px solid #191919;
    border-right: 100px solid #5DBCF9;
  }
  div::before {
    --m: -25 -25;
    --p: 25;
    --b: #5DBCF9;
    border-radius: 10px 0 0 10px;
  }
  div::after {
    --p: 100 50;
    --m: -100 125; 
    --b: radial-gradient(circle at 0 50%, #191919 28.5%, #5DBCF9 0, 35.5%, #191919 0, 46%, #5DBCF9 0, 53%, #191919 0, 64%, #5DBCF9 0, 71%, #191919 0)
  }
</style>
```