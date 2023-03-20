# 58 Rose

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16775646335237/16775646421343.png)

## done

```html
<p></p><i><i><i>
<style>
  *, p::after {
    position: absolute;
    margin: var(--m);
    padding: var(--p);
    border-radius: var(--r);
    background: var(--b, #191919);
  }
  p {
    --m: 175 190;
    --p: 40 10;
    --b: #F9E492;
    --r: 10px;
  }
  p::after{
    content: '';
    --b: #4F77FF;
    --p: 50;
    --m: -150 -50;
    --r: 50%;
    box-shadow: 0 50px 0 -30px #F9E492;
  }
  i {
    --p: 15 70;
    --m: 75 120;
    --r: 15px 15px 35px 35px;
    --b: #4F77FF;
    border: 10px solid #191919;
  }
  i i {
    --p: 15 50;
    --m: -45 -60
  }
  i i i {
    --p: 15;
    --r: 50%;
    --m: -45 -25;
  }
</style>
```
