# 96 Mandala 未完成

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16783688476039/16783688539344.png)

## done

搞不清楚为啥 99.8%

```html
<img><i><i>
<style>
  * {
     position: absolute;
     margin: var(--m);
     padding: var(--p);
     border-radius: var(--r, 50%);
     background: var(--b, #243D83);
  }
  img {
    --p: 100;
    --b: #6592CF;
    --m: 50 100;
  }
  i {
    --p: 65;
    border: 20px solid #243D83;
    --m: 65 40; 
    --b: transparent;
    -webkit-box-reflect: var(--t, right) -20px;
  }
  i i {
    --m: -10;
    --t: above;
  }
</style>
```