# 70 Froggy

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16777430838360/16777430965096.png)

## done

```html
<o><i></i></o><u>
<style>
  * {
    position: absolute;
    margin: var(--m);
    padding: var(--p);
    border-radius: var(--r, 50%);
    background: var(--b, #293462);
  }
  o {
    --p: 50 75;
    --m: 110 125;
    --b: #A64942;
    --r: 50px;
    overflow:hidden;
  }
  i {
    --p: 200;
    --m: -380 -200;
    --r: 50%;
    --b: #FE5F55;
  }
  u {
    --p: 25;
    --b: #293462;
    --m: 85 140;
    --b: radial-gradient(#293462 15%, #FFF1C1 0, 42%, #FE5F55 0);
    box-shadow: 25px 55px 0 -20px #293462;
    -webkit-box-reflect: right 20px;
  }
</style>
```