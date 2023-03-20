# 75 Hippo

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16779816604045/16780041274689.png)

## done

```html
<img><img><p></p><img><img>
<style>
  *, p::before, p::after {
    content: '';
    position: absolute;
    margin: var(--m);
    padding: var(--p);
    border-radius: var(--r);
    background: var(--b, #191919);
    transform: rotate(var(--t));
  }
  p {
    --p: 80 65;
    --m: 75 135;
    --r: 60px;
    --b: #FE5F55;
  }
  p::before {
    --b: #A64942;
    --p: 50 75;
    --r: 55px 55px 45px 45px;
    --m: -10 -75; 
  }
  p::after {
    --r: 50%;
    --p: 5;
    --m: -30 30;
    --b: #000000;
    box-shadow: -70px 0;
  }
  img {
    --p: 5 10;
    --r: 50%;
    --m: 75 145;
    --t: 45deg;
    --b: #000000;
    border: 5px solid #FE5F55;
  }
  img + img {
    --m: 75 225;
    --t: -45deg;
  }
  p ~ img  {
    --m: 170 145;
    --t: -45deg;
    border-color: #000000;
  }
  p + img + img {
    --m: 170 225;
    --t: 45deg;
  }
</style>
```