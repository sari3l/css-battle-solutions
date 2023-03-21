# 34 Christams Tree

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16773983304399/16773983462226.png)

## done

```html
<div></div>
<style>
  body {
    background: #007065;
  }
  div, div::before, div::after {
    content: '';
    position: absolute;
    border: 125px solid transparent;
    border-bottom: 100px solid #00A79D;
    left: 75;
    top: 25;
  }
  div::before {
    top: -175;
    left:-125;
    border-bottom-color: #F5C181;
  }
  div::after {
    top: -225;
    left:-125;
    border-bottom-color: #FFEECF;
  }
</style>
```