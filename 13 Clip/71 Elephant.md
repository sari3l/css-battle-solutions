# 71 Elephant

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16777474642925/16777474685980.png)

## done

```html
<i><i></i></i><o><b><b></b></b><g>
<style>
  * {
    position: absolute;
    margin: var(--m);
    padding: var(--p);
    border-radius: var(--r,50%);
    background: var(--b, #998235);
  }
  i {
    --p: 90 40;
    --m: 60 50;
    --b: #1A4341;
    overflow: hidden;
    -webkit-box-reflect: right 140px;
  }
   i i {
     --m: -90 -24;
     --b: #0B2429;
   }
  o {
    --p: 90;
    --b: #1A4341;
    --m: 60 110;
  }
  b {
    --m: 40 -60;
    --p: 30 60;
    --r: 0;
    --b: radial-gradient(at 50% 100%, transparent 47%, white 0, 71%, transparent 0);
  }
  b b {
    --p: 10 20;
    --b: radial-gradient(at 50% 0, #0B2429 35%,  #998235 0, 70%, #1A4341 0);
    --m: -70 10;
    -webkit-box-reflect: left 20px;
  }
  g {
    --p: 80 20;
    --r: 20px;
    --m: 30 -20;
    --b: #0B2429;
  }
</style>
```