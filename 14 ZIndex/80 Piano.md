# 80 Piano

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16781605821835/16781746730102.png)

## done

```html
<u><i><i><o><i><i><i><o>
<style>
  *, i::after{
    content: '';
    position: absolute;
    margin: var(--m);
    padding: var(--p);
    border-radius: var(--r, 10px);
    background: var(--b, #998235);
  }
  u {
    --p: 50 90;
    --m: 100 110;
    --b: #191919;
  }
  i {
    --p: 35 10;
    --r: 5px;
    --m: -25 -85;
    --b: #FFFFFF;
  }
  i i {
    --m: -35 15;
  }
  i::after {
    --p: 17.5 7.5;
    --r: 0;
    --m: -35 5;
    --b: #191919;
  }
</style>
```