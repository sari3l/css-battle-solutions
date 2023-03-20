# 82 Diamond Cut

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16781751311949/16781751401250.png)

## 分析

中间应该有mix-blend-mode的使用，但是懒得搞了

## done

```html
<img><img><img>
<style>
  *{
    position: absolute;
    margin: var(--m);
    padding: var(--p);
    background: var(--b, #F3AC3C);
    border: var(--r);
  }
  img {
    --p: 50;
    --m: 70 118;
    --r: 30px solid #998235;
    transform: rotate(45deg);
  }
  img + img {
    --m: -22 118;
    --b: transparent;
    --r: 30px solid #F3AC3C;
  }
  img + img + img {
    --p: 0;
    --m: 135 183;
    --r: 15px solid #1A4341;
  } 
</style>
```