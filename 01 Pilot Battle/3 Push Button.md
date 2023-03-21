# 3 Push Button

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16772259527543/16772259623002.png)

## done

```html
<div></div>
<style>
  * {
    background: #6592CF;
  }  
  div, div::after {
    position: absolute;
    left: 50;
    top: 75;
    width: 300px;
    height: 150px;
    background: #243D83;
  }
  div::after {
    content: '';
    top: -50;
    left: 25;
    height: 250px;
    width: 250px;
    border-radius: 50%;
    background: radial-gradient(#EEB850 0, 25px, #243D83 0, 75px, #6592CF 0);
  }
</style>
```