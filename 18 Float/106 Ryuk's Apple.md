# 106 Ryuk's Apple

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16792283058865/16792283144885.png)

## done

```html
<p><b>
<style>
  *, :after {
    content: '';
    position: absolute;
    margin: var(--m);
    padding: var(--p);
    border-radius: var(--r);
    background: var(--b, #000);
  }
  b {
    --p: 20 5;
    --b: #D4392D;
    --m: 70 195;
    -webkit-box-reflect: left -10px;
  }
  b::after {
    --p: 60 50;
    --b: #D4392D;
    --m: 0 -20;
    --r: 50%;
    transform: rotate(28deg);
  }
  p:after {
    --p: 26;
    --r: 50%;
    --m: 100 100;
    box-shadow: 0 41px;
  }
</style>
```