# 26 Smiley

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16774146704240/16774152373598.png)

## done 

```html
<div></div>
<style>
  * {
    background: #6592CF
  }
  div, div::before, div::after {
    position: absolute;
    content: '';
    width: 80;
    height: 80;
    border-radius: 50%;
    margin: 32 32;
    border: 20px solid;
    border-color: #060F55 transparent transparent #060F55  ;
    transform: rotate(45deg);
  }
  div::before {
    margin: -161.5 121;
    transform: rotate(0deg);
  }
  div::after {
    margin: -20 122;
    transform: rotate(180deg);
  }
</style>
```