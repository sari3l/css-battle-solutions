# 69 PushOwl

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16776731674882/16776731751782.png)

## done

真的难顶，这个布局可以多想想，因为中间有个多出来的方框导致比较难整不能镜像

```html
<i><b><i></i></b></i><img><i><b><i>
<style>
  * {
    position: absolute;
    margin: var(--m);
    padding: var(--p);
    border-radius: var(--r);
    background: var(--b, #191919);
  }
  i{
    --b: radial-gradient(circle, #191919 var(--c, 45px), #e08027 0);
    border: 10px solid #191919;
    --p: 57;
    --m: 67 79;
    border-radius: var(--r, 0) 50%50%;
  }
  b {
    --p: 15;
    --m: -24 -15;
    --r: 0;
    overflow:hidden;
  }
  i i {
    --p: 15;
    --c: 6px;
    --m: -10 -25;
    --r: 50%;

  }
  img {
    --p: 25;
    --b: #E08027;
    --m: 162 175;
    transform: rotate(45deg);
  }
  img + i {
    --m: 67 187;
    --r: 50% 0;
  }
</style>
```