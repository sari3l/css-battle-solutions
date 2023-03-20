# 112 Chevron

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16789593632356/16789593728896.png)

## done

```html
<img><img><img>
<style>
  * {
    position: absolute;
    margin: var(--m);
    padding: var(--p);
    background: var(--b, #6592CF);
  }
  img {
    --p: 50 125;
    --b: #293D7E;
    --m: 50 75;
    clip-path: polygon(15.5% 0, 50% 69%, 84.5% 0, 100% 0, 50% 100%, 0 0);
  }
  img + img {
    --m: 100 75;
  }
  img + img + img {
    --m: 150 75;
  }
</style>
```