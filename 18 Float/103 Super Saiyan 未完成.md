# 103 Super Saiyan 未完成

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16789688410496/16792176449736.png)

## done

99.9%

```html
<b><t></t><t></t><r>
<style>
  *, ::before, ::after {
    content: '';
    position: fixed;
    margin: var(--m);
    border-radius: var(--r);
    background: var(--b, #161616);
    width: 50%
  }
  t {
    width: 80;
    height: 60;
    --b: linear-gradient(90deg, #FFFFFF 50%, #FFDEB9 0);
    --m: 156 160;
    --r: 0 0 40px 40px;
  }
  t + t {
    width: 20;
    height: 10;
    --m: 196 190;
    --b: #161616;
  }
  b, r {
    -webkit-box-reflect: right 0;
  }
  b::before, r::before, r::after {
    width: 60;
    height: 60;
    --b: #EBAE11;
    --r: 50%;
    --m: 130.5 141;
    clip-path: polygon(0 36%, 100% 65%, 100% 100%, 0 100%);
  }
  r::before {
    --m: 112 155;
    clip-path: polygon(20% 0, 77% 100%, 0 100%, 0 0)
  }
  r::after {
    --m: 66 182;
    width: 120;
    height: 120;
    clip-path: polygon(0 0, 15.5% 0, 15.5% 90%, 0 90%)
  }
</style>
```