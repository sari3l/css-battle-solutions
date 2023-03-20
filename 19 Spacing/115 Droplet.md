# 115 Droplet

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16789606430945/16789606490885.png)

## done

```html
<div><i></i><i></i><img></div>
<style>
  * {
    position: absolute;
    margin: var(--m);
    padding: var(--p);
    border-radius: var(--r);
    background: var(--b, linear-gradient(#C36271 50%, #F2E09F 0));
  }
  div {
    --p: 150 200;
  }
  i {
    --p: 75 300;
    --b: #C36271;
    --m: 0 -180;
    --r: 100px 0
  }
  i + i {
    --m: -150 -420;
    --b: #F2E09F;
  }
  img {
    --p: 50;
    --r: 50%;
    --m: -50
  }
</style>
```