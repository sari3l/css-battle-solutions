# 42 Baby

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16774176149606/16774176232585.png)

## done

```html
<div></div>
<style>
  * {
   background: #293462;
  }
  div {
    position: absolute;
    margin: 42 92;
    width: 200;
    height: 200;
    background: #FE5F55;
    overflow: hidden;
    border-radius: 100px 100px 50px 50px;
  }
  div::before, div::after {
    content: '';
    position: absolute;
    background: #FFF1C1;
  }
  div::before {
    margin: 90 20;
    width: 60;
    height: 60;
    border-radius: 50%;
    box-shadow: 100px 0 #FFF1C1, 0 -120px 0 20px #FFF1C1, 100px -120px 0 20px #FFF1C1;
  }
  div::after {
    margin: 170 80;
    width: 40;
    height: 10;
    border-radius: 5px;
  }
</style>
```