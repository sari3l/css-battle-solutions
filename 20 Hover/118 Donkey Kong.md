# 118 Donkey Kong

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16792057825487/16792057930093.png)

## done

```html
<i><i><i><o><img><o>
<style>
  * {
    position: absolute;
    margin: var(--m);
    padding: var(--p);
    border-radius: var(--r);
    background: var(--b, #000);
  }
  i {
    --m: 100 80;
    --p: 30 10;
    --b: #FFF;
  }
  i i {
    --m: 15 100;
  }
  i i i {
    --m: -70 100;
    --p: 50 10;
  }
  o {
    --r: 10px;
    --p: 10 150;
    --b: #AF067C;
    --m: -65 -260;
  }
  o img {
    --m: 40 -150;
    transform: rotate(-4deg);
  }
  o o {
    --m: 90 -150;
  }
</style>
```