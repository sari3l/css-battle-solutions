# 93 Great Wall

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16783667998154/16783668063461.png)

## done

```html
<u><i><i><i><u>
<style>
   *, i::before, i::after {
     content:'';
     position: absolute;
     margin: var(--m);
     padding: var(--p);
     border-radius: var(--r);
     background: var(--b, #4F77FF);
  }
  u {
    --r: 50%;
    --p: 100;
    --m: 50 100;
    --b: #191919;
    overflow: hidden
  }
  i::before {
    --r: 0;
    transform: skewY(-33deg);
    --p: 8 10;
    --m: -14.5 50;
    --b: #D6B73F
  }
  i, i::after{
    --p: 8 50;
    --r: 0;
  }
  i {
    --m: 22 -100;
    --b: #F9E492;
  }
  i::after {
    --m: -21 70;
  }
  i i {
    --m: 18 -50;
  }
  i u {
    --b: #F9E492;
    --p: 20;
    --m: -142 -10;
  }
</style>
```