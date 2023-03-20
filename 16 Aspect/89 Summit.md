# 89 Summit

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16781785052220/16781785155592.png)

## 分析

忘记了`radial-gradient`

## done

```html
<img><i>
<style>
  * {
    position: absolute;
    margin: var(--m);
    padding: var(--p);
    border-radius: var(--r);
    background: var(--b, #191919);
  }
  img {
    --p: 100;
    --r: 50%;
    --m: 50 100;
    --b: #F9E492;
    overflow:hidden;
  }
  i {
    --p: 120;
    --m: 208 80;
    transform: rotate(45deg);
    --b: radial-gradient(at -6px -6px,#191919 100px, #4F77FF 0);
  }
</style>
```