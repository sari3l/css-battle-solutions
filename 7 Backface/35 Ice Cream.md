# 35 Ice Cream

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16774007673830/16774008004673.png)

## done

```html
<div></div>
<style>
  * {
    background: #293462;
  }
  div {
    position:absolute;
    width: 100;
    height: 150;
    top: 50;
    left: 150;
    border-radius: 50px 50px 20px 20px;
    background: #FFF1C1;
  }
  div::before, div::after {
    position:absolute;
    content: '';
    height: 50;
    width: 30;
    top: 150;
    left: 35;
  }
  div::before {
    background: #FE5F55;
    border-radius: 0 0 10px 10px;
  }
  div::after {
    top: 150;
    height: 10;
    background: #A64942
  }
</style>
```