# 74 Danger Noodle

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16778374160180/16778374205721.png)

## done

```html
<p><img></p><p><img></p><img><img><u><b><i>
<style>
  *, p::before, p::after {
    content: '';
    position: absolute;
    margin: var(--m);
    padding: var(--p);
    border-radius: var(--r);
    background: var(--b, #191919);
  }
  img {
    --p: 17.5 35;
    --m: 125 -35;
    --b: radial-gradient(at var(--z, 50% 0),#191919 30%, #E08027 0, 41%, #191919 0, 61%, #E08027 0, 70%, #191919 0) 
  }
  img + img {
    --m: 140 215;
    --p: 17.5;
    --z: 100% 100%
  }
  p img {
    --m: 40 15;
    --z: 50% 100%;
  }
  p::before {
    --m: 70 15;
    --p: 40 5;
    border: solid #E08027;
    -webkit-box-reflect: right 30px;
    border-width: 0 5px;
  }
  p {
    -webkit-box-reflect: right 200px;
  }
  p + p {
    --m: 300 50;
    transform: scaleY(-1);  
  }
  u {
    --m: 140 250;
    --p: 5 10;
    border: solid #E08027;
    border-width: 5px 0;
  }
  b {
    --p: 15 25;
    --b: #E08027;
    --m: -15 5;
    --r: 10px 15px 15px 10px;
  }
  i {
    --b: #191919;
    --p: 5;
    --m: 3 5;
    box-shadow: 0px -15px #191919;
  }
</style>
```