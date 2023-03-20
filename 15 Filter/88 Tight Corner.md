# 88 Tight Corner

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16781779614262/16781779703490.png)

## done

```html
<img><i>
<style>
  *{
    position: absolute;
    margin: var(--m);
    padding: var(--p);
    border-radius: var(--r, 10px);
    background: var(--b, #F7F3DA);
    box-shadow: var(--s);
  }
  img {
    --p: 20 110;
    --m: 110 -20;
    --b: #D25B70;
    --s: 220px 40px #D25B70;
  }
  i {
    --p: 120;
    --m: 150 -40;
    --r: 20px;
    --s: 240px -240px #F7F3DA, 120px -120px 0 -100px #D25B70;
  }
</style>
```