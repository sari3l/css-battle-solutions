# 97 Snowman

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16784147389312/16784147507070.png)

## done

```html
<img><u><i><i>
<style>
  * {
     position: absolute;
     margin: var(--m);
     padding: var(--p);
     border-radius: var(--r, 50%);
     background: var(--b, #AC474B);
  }
  img {
    --r: 50%;
    --p: 50;
    --b: #FFF;
    --m: 145 150;
    box-shadow: -10px -77px 0 -45px #0E1F2B, 10px -77px 0 -45px #0E1F2B, 0 -70px 0 -20px #FFF;
  }
  u {
    --p: 9 38;
    --r: 10px;
    --m: 139 162
  }
  i {
    --p: 5 30;
    --b: #FFA63F;
    --m: -5 -30
  }
  i i {
    --p: 22.5 30;
    --m: -93 -30;
    --r: 0;
    --b: linear-gradient(#0E1F2B 34%, #FFF 0, 55%, #0E1F2B 0);
    clip-path: polygon(0 89%, 17% 89%, 17% 0, 83% 0, 83% 89%, 100% 89%, 100% 100%, 0 100%);
  }
</style>
```