# 102 One Piece

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16786025948879/16786026015862.png)

## done

```html
<u><img><i></i></u><o>
<style>
  *, i::before, i::after {
    content: '';
    position: absolute;
    margin: var(--m);
    padding: var(--p);
    border-radius: var(--r);
    background: var(--b, #000);
  }
  u {
    --p: 50 37.5;
    --b: #FFF;
    --r: 50px 0 0 50px;
    --m: 110 125;
    -webkit-box-reflect: right 0px;
  }
  img {
    --p: 20 25;
    --m: -20 -18;
    --r: 50%;
    --b: #000;
    transform: rotate(-30deg)
  }
  i {
    --p: 12.5;
    --r: 50%;
    --m: -75 -58;
    -webkit-box-reflect: below 100px; */
  }
  i::before {
    --p: 12.5;
    --r: 50%;
    --m: -3 -22;
  }
  i::after {
    --p: 10;
    --r: 0;
    --m: 5 -4;
    transform: rotate(45deg);
  }
  o {
    --p: 10 27.5;
    --b: linear-gradient(90deg, #FFF 28%, #000 0 36%, #FFF 0 63%, #000 0 72%, #FFF 0);
    --m: 220 173;
  }
</style>
```