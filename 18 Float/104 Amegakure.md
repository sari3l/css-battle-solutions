# 104 Amegakure

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16789688452344/16789688538279.png)

## done

```html
<p></p><u></u><i><img><img><i><i>
<style>
  * {
    position: absolute;
    margin: var(--m);
    padding: var(--p);
    border-radius: var(--r);
    background: var(--b, #000);
  }
  p {
    --p: 60 120;
    --b: #37385A;
    --r: 20px;
    --m: 90 80;
  }
  u {
    --p: 40 100;
    --b: linear-gradient(-75deg, #9897AE 38.5%, #C0C3DB 0 61.5%, #9897AE 0 );
    --m: 110 100;
    --r: 10px;
  }
  i {
    --p: 5;
    --b: #000;
    --r: 50%;
    --m: 125 115;
    -webkit-box-reflect: right 150px;
  }
  i i {
    --m: 15 -5
  }
  img {
    --p: 25 5;
    --r: 5px;
    --m: -5 45;
  }
  img + img {
    --m: -5 65;
  }
</style>
```