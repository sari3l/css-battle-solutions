# 73 Happy Tiger

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16778285565162/16778285654861.png)

## done

别问，问就是丑陋


```html
<img><i><img><b></b><u><u></u><i><img>
<style>
  * {
    position: absolute;
    margin: var(--m);
    padding: var(--p);
    border-radius: var(--r,50%);
    background: var(--b, #F3AC3C);
  }
  img {
    --m: 65 115;
    --p: 20px;
    --b: #1A4341;
    border: 10px solid #998235;
    -webkit-box-reflect: right calc((60px - var(--p)/2));
  }
  i {
    --p: 75 75;
    --m: 75 125;
    --b: #998235;
    --r: 50% 50% 40% 40%;
    overflow: hidden;
  }
  i img {
    --p: 0px;
    border-color: #1A4341;
    --m: -15 -50;
    --r: 50%;
  }
  b {
    --r: 0;
    --p: 20;
    --m: -98 -20;
    transform: rotate(45deg);
    --b: #1A4341;
  }
  i u, u i {
    --p: 20 50;
    --b: #FFFFFF;
    --m: 20 -50;
    --r: 12px 12px 30px 30px;
  }
  u i {
    --b: #0000;
    --m: -10 -50;
  }
  u u {
    --p: 15 5;
    --b: #1A4341;
    --m: -30 -5;
  }
  u img{
    --p: 10;
    --r: 50%;
    --b: transparent;
    --m: -40 -35;
    -webkit-box-reflect: right -10px;
  } 
</style>
```