# 64 Door Knob

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16776627290431/16776627393731.png)

## done

丑陋

```html
<p><u><i>
<style>
  * {
    content: '';
    position: absolute;
    margin: var(--m);
    padding: var(--p);
    border-radius: 50%;
    background: var(--b, #191919);
  }
  p {
    --p: 80;
    --m: 70 120;
    --b: radial-gradient(#E08027 50px, #824B20 0)
  }
  u {
    --p: 10;
    --m: -10 -60;
    --b: #FFF58F;
    box-shadow: 100px 0 #FFF58F;
  }
  i {
    --p:40;
    background: transparent;
    --m: -60 -10;
    border: 20px solid;
    border-color: transparent #FFF58F #FFF58F transparent ;
    transform: rotate(45deg)
  }
</style>
```