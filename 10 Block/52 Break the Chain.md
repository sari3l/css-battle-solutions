# 52 Break the Chain

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16775027616181/16775028389594.png)

## done

```html
<img><u><i><i><i><u><i><i><i><i>
<style>
  * {
    background: #6592CF;
  }
  * *, i::after {
    position: absolute;
    margin: var(--m);
    padding: var(--p);
    border-radius: var(--r);
    background: var(--b);
  }
  i {
    --p: 25 5;
    --m: -25 40;
    --b: #243D83;
  }
  u u {
    --p: 0 20;
    --m: 0 10;
  }
  u {
    --m: 165 5;
    --b: #6592CF;
  }
  i::after, img {
    content: '';
    --b: #243D83;
    --p: 10;
    --m: -35 -10;
    --r: 50%;
  }
  img {
    --p: 20;
    --m: 120 30;
    --b: #EEB850;
    box-shadow: 45px -10px 0 10px #EEB850, 90px 0 #EEB850;
  }
</style>
```