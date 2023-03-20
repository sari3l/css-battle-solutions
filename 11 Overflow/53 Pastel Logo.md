# 53 Pastel Logo

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16775051673211/16775052040454.png)

## 分析

我始终认为cssbattle的后端有问题，明明overlay就能解决，但是判定96.5%?

```html
<i><t>
<style>
  body {
    background: #19191A;
  }
  i {
    margin: 42 117;
    padding: 75;
    background: #4F77FF;
    border-radius: 50%;
    position: absolute;
  }
  t {
    position: absolute;
    margin: 0 -75;
    padding: 62.5 37.5;
    background: #F9E492;
    mix-blend-mode: overlay;
  }
</style>
```

## done

```html
<img><i><img>
<style>
  * {
    background: #19191A;
  }
  * * {
    margin: var(--m);
    padding: var(--p);
    background: var(--b);
    position: absolute;
  }
  img {
    --p: 75;
    --b: #4F77FF;
    --m: 50 125;
    --p: 75;
    border-radius: 50%;
  }
  i img{
    --m: -138 -38;
    --b: #9AD5FF;
  }
  i {
    --m: 125 125;
    --p: 62.5 37.5;
    --b: #F9E492;
    overflow: hidden;
  }
</style>
```