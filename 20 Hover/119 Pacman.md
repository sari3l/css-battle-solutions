# 119 Pacman

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16792062664813/16792062728672.png)

## done

```html
<img><img><t></t><o><i>
<style>
  * {
    position: absolute;
    margin: var(--m);
    padding: var(--p);
    border-radius: var(--r);
    background: var(--b, #000);
  }
  img {
    --p: 30;
    --b: #E0E246;
    --r: 50%;
    --m: 120 60;
  }
  img + img {
    --r: 0%;
    --p: 20;
    --b: #000;
    transform: rotate(45deg);
    --m: 130 95;
  }
  t {
    --p: 5;
    --b: #FFF;
    --r: 50%;
    --m: 145 165;
    box-shadow: 30px 0 #FFF, 60px 0 #FFF;
  }
  o {
    --b: #C74E4E;
    --p: 30;
    --r: 50% 50% 0 0;
    --m: 120 280;
  }
  i {
    --b: #000;
    --p: 8;
    --m: 21 -28;
    --r: 0;
    transform: rotate(45deg);
    box-shadow: 14px -14px, 28px -28px;
  }
</style>
```