# 107 Sealing Wand

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16792291835905/16792291913955.png)

## done

```html
<p><i>
<style>
  *, :after, :before {
    content: '';
    position: absolute;
    margin: var(--m);
    padding: var(--p);
    border-radius: var(--r);
    background: var(--b, #161616);
  }
  p {
    --p: 20 40;
    --b: #E96A23;
    --m: 129 200;
    --r: 0 40px 5px 0;
  }
  p::before {
    --p: 80 10;
    --b: #E96A23;
    --m: 0 -50;
  }
  p::after {
    --p: 14 15;
    --r: 0 0 10px 10px;
    --b: #A22015;
    --m: 26 -55;
  }
  i {
    --p: 30;
    --r: 50%;
    --b: #A22015;
    --m: -29 -70;
  }
  i::before {
    --b: #FFF;
    --p: 7 28;
    --r: 0 0 0 12px;
    --m: 4 -40;
    box-shadow: -15px -12px #FFF, -31px -23px 0 -1px #FFF;
  }
  i::after {
    --m: -25;
    --p: 25;
    --b: radial-gradient(#161616 28%, #A22015 0 42.5%, #FFF 0)
  }
</style>
```