# 141 Third Eye

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16791975787774/16791975880501.png)

## done

```html
<img><i><img>
<style>
  * {
    position: absolute;
    margin: var(--m);
    padding: var(--p);
    border-radius: var(--r);
    background: var(--b, #E3516E);
  }
  img {
    --b: #D9D9D9;
    --p: 75;
    --r: 50%;
    --m: -75;
    box-shadow: 400px 300px #D9D9D9;
  }
  i {
    --p: 14.5 70;
    --m: 121 130;
    overflow: hidden;
    -webkit-box-reflect: below 0;
  }
  i img {
    --p: 100;
    --m: -15 -100;
  }
</style>
```