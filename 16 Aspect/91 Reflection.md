# 91 Reflection

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16783652797169/16783652893864.png)

## done

```html
<img><i><i><i><i>
<style>
  * {
    position: absolute;
    margin: var(--m);
    padding: var(--p);
    border-radius: var(--r);
    background: var(--b, #6CB3A9);
  }
  body{
     inset: 0;
     --p: 150 200;
     --b: linear-gradient(#D25B70 50%, #6CB3A9 0);
  }
  img {
    --p: 100;
    --r: 50%;
    --m: -100;
    --b: #F6DF96;
  }
  i {
    --p: 7.5 100;
    --m: 0 -100;
    --b: #6CB3A9;
  }
  i i {
    --m: 17.5 -100;
  }
</style>
```