# 114 Negative Box

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16789602067862/16789602135883.png)

## done

```html
<img><img>
<style>
  * {
    position: absolute;
    margin: var(--m);
    padding: var(--p);
    background: var(--b, #172D2C);
    clip-path: var(--c)
  }
  img {
    --p: 100 90;
    --b: #E9AF53;
    --m: 85 20;
    --c: polygon(0 0, 100% 32.5%, 100% 97.5%, 0 65%)
  }
  img + img {
     --m: 20 200;
     --c: polygon(0 0, 100% 32.5%, 0 65%)
  }
</style>
```