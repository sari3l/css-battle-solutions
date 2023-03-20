# 84 Junction

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16781763608053/16781763679050.png)

## done

```html
<img><img>
<style>
  *{
    position: absolute;
    margin: var(--m);
    padding: var(--p);
    border-radius: var(--r, 20px);
    background: var(--b, #191919);
    -webkit-box-reflect: var(--t, below) 40px;
  }
  img {
    --p: 80 20;
    --b: #FE5F55;
    --m: -30 180;
  }
  img + img {
    --p: 20 105;
    --m: 130 -30;
    --t: right;
    --b: #A64942;
  }
</style>
```