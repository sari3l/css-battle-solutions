# 72 Sheep

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16778250162208/16778250234126.png)

## done

```html
<i></i><p><u><b></b>
<style>
  *, u::before, u::after {
    content: "";
    position: absolute;
    margin: var(--m);
    padding: var(--p);
    border-radius: var(--r,50%);
    background: var(--b, #243D83);
  }
  i {
    --p: 34;
    --b: #6592CF;
    --m: 116 115;
    box-shadow: 51px 51px #6592CF, 17px 34px #6592CF;
    -webkit-box-reflect: right 34px;
  }
  p {
    --b: #243D83;
    --p: 35 30;
    --r: 30px;
    --m: 105 170;
  }
  u {
    --p: 25 30;
    --m: -75 -30;
    --r: 50%;
    --b: #6592CF;
  }
  u::before{
    --m: -5 -70;
    transform:rotate(-45deg);
  }
  u::after{
    --m: -5 10;
    transform:rotate(45deg);
  }
  b {
    --p: 5;
    --m: 40 5;
    -webkit-box-reflect: left 10px;
  }
</style>
```