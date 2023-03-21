# 40 Letter B

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16774026381806/16774028680732.png)

## 分析

`border + 竖`比较直接，但实际可以看为一个封闭的图形多了一个竖截断

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16774026381806/16774028551065.jpg)

## done

```html
<div></div>
<style>
  * {
    background: #6592CF;
  }
   div {
     position: absolute;
     height: 100;
     width: 100;
     top: 50;
     left: 100;
     border: 50px solid #243D83;
     border-radius: 0 50% 50%; 
  }
  div::before {
    content: '';
    position: absolute;
    height: 50;
    width: 50;
    top: -50;
    background: #6592CF;
  }
</style>
```

