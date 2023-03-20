# 140 Eclipse

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16770567597467/16770567868718.jpg)

伪类永远的神

## done

```html
<div></div>
<style>
*{
  background: #4F77FF;
}  
  div, div::before {
    margin: 50px 152px;
    width: 80px;
    height: 80px;
    border-radius: 50%;
    background: #FFFFFF;
    position:relative;
  }
  div::before {
    content: '';
    position:absolute;
    margin: 40px 0px;
    background: #4F77FF;
  }
  div::after {
    content: '';
    position:absolute;
    width: 300px;
    height: 300px;
    background: #1038BF;
    rotate: 45deg;
    margin: 150px -110px;
  }
</style>
```
