# 56 Skull

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16775110361796/16775110515901.png)

## done

```html
<img><img><p><i><o>
<style>
  * {
    position: absolute;
    margin: var(--m);
    padding: var(--p);
    border-radius: var(--r);
    background: var(--b, #191919);
  }
  img {
    --p: 50 60;
    --b: #4F77FF;
    --m: 85 140;
    --r: 60px 60px 10px 10px;
  }
  img + img {
    --p: 15 40;
    --m: 185 160;
    --r: 0 0 20px 20px;
  }
  p {
    --p: 20;
    --m: 59 67.5;
    --r: 50%;
    --b: #191919;
    box-shadow: 137px 79px #191919, 112px 107px 0 -10px #191919;
  }
  o {
    --p: 10 5;
    --m: 47 5;
    --r: 5px;
    --b: #191919;
    box-shadow: 15px 0 #191919, 30px 0 #191919;
  }
</style>
```