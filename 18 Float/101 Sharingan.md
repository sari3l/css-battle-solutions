# 101 Sharingan

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16784283925387/16784284055572.png)

## done

```html
<i><img><img><img>
<style>
  * {
    position: absolute;
    margin: var(--m);
    padding: var(--p);
    border-radius: 50%;
    background: var(--b, #161616);
  }
  i {
    --p: 100;
    --b: radial-gradient(#000 25px, #E96A23 0 35px, #000 0 50px, #A22015 0 95px, #000 0);
    --m: 50 100;
    overflow: hidden
  }
  img {
    --p: 35;
    --b: #0000;
    border: 15px solid #000;
    --m: -92 -123;
  }
  img + img {
    --m: -92 23
  }
  img + img + img {
    --m: 35 -50
  }
</style>
```