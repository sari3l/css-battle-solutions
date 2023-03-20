# 47 Corona Virus

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16774821625343/16774821734968.png)

## 分析

要写一堆伪类太离谱，明明就是一个棍翻转+各种圆阴影

## done

其实这样写不好，但是吧，就是玩

```html
<div><img><img><img><p><p><p><p>
<style>
  * {
    background: #1A4341;
  }
  div * {
    position: absolute;
    padding: var(--p, 90 5);
    margin: var(--m, 42 187);
    border-radius: var(--r, 5px);
    transform: rotate(calc(var(--n, 0)*60deg));
    transform-origin: 5px 100px;
    background: var(--b, #F3AC3C);
  }
  * + img {
    --n: 1;
  }
  * + * +img {
    --n: 2;
  }
  p {
    --r: 50%;
  }
  * > p {
    --p: 50;
    --m: 92 142;
  }
  p ~ p {
    --p: 15;
    --m: 112 162;
    --b: #998235;
  }
  p + * + p {
    --p: 10;
    --m: 157 182;
  }
  p + p + p + p {
    --p: 5;
    --m: 112 212;
  }
```