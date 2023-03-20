# 109 Curtain

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16789575561643/16789579983252.png)

## done

```html
<img>
<style>
  * {
    position: absolute;
    margin: var(--m);
    padding: var(--p);
    background: var(--b, #191919);
  }
  img {
    --p: 150 200;
    --b: linear-gradient(135deg, #0000 205px, #191919 0) no-repeat 0 / 400px,
      radial-gradient(#F6E59C 20px , #191919 0) 10px 10px / 60px 60px;
  }
</style>
```