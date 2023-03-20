# 111 Rain Drops

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16789589216710/16789589274094.png)

## done

```html
<img><img><img>
<style>
  * {
    position: absolute;
    margin: var(--m);
    padding: var(--p);
    border-radius: 40px 40px 0;
    transform: rotate(var(--r));
    background: var(--b, #F3AC3C);
  }
  img {
    --p: 40;
    --b: #254241;
    --m: 40 160;
    --r: 45deg;
  }
  img + img {
    --r: -45deg;
    --m: 110 80;
  }
  img + img + img {
    --r: -135deg;
    --m: 180 160;
  }
</style>
```