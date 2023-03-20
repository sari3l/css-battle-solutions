# 87 Building Blocks

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16781773545511/16781773619319.png)

## done

```html
<div></div><div>
<style>
  *, div::after, div::before{
    content: '';
    position: absolute;
    margin: var(--m);
    padding: var(--p);
    border-radius: 10px;
    background: var(--b, #F3AC3C);
  }
  div {
    --p: 25 75;
    --m: 65;
    --b: #1A4341;
  }
  div::before {
    --p: 50;
    --m: -25 -75;
  }
  div::after {
    --p: 20;
    --m: 25;
    --b: #F3AC3C;
    box-shadow: -5px -5px #1A4341;
  }
  div + div {
    transform: rotate(180deg);
    transform-origin: 135px 85px;
  }
</style>
```