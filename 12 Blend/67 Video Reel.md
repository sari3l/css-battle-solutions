# 67 Video Reel

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16776718462617/16776718532883.png)

## done

```html
<i><i><i><i>
<style>
  *, i::before, i::after{
    content: '';
    position: absolute;
    margin: var(--m);
    padding: var(--p);
    background: var(--b, #5DBCF9);
  }
  i {
    --p: 55 70;
    --b: #191919;
    --m: 120 -95;
  }
  i::before{
    --m: -205 -70;
  }
  i::after{
    --m: 95 -70;
  }
  i i {
    --m: -105 80;
  }
  i i i {
    --m: -5 80;
  }
  i i i i {
    --m: -105 80;
  }
</style>
```