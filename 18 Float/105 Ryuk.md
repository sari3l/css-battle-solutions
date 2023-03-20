# 105 Ryuk

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16792271833171/16792272018638.png)

## done

```html
<p><i>
<style>
  *, :before, :after{
    content: '';
    position: absolute;
    margin: var(--m);
    padding: var(--p);
    border-radius: var(--r);
    background: var(--b, #BAC7CE);
  }
  p {
     -webkit-box-reflect: right 400px;
  }
  p::after {
    --p: 70;
    --b: #475862;
    transform: rotate(45deg);
    --m: -78 130;
  }
  p::before {
    --p: 60;
    --b: #000;
    --r: 50% 0;
    --m: 130 30;
    transform: rotate(75deg);
  }
  i, i::before{
    --p: 50;
    --r: 50%;
    --b: #5A6042;
    --m: 140 40;
    overflow: hidden;
  }
  i::before {
    --b: #868A64;
    --m: -35 -50;
  }
  i::after {
    --p: 15;
    --m: -20;
    --b: #4E2B24;
    border: 5px solid;
  }
</style>
```