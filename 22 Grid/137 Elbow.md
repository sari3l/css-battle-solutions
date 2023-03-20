# 137 Elbow

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16770515603756/16770516866710.jpg)

## 分析

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16770515603756/16770516729327.jpg)

两个左上圆角矩形叠加

## done

```html
<div class='g'></div>
<style>
  * {
    background: #6592CF;
  }
  .g {
    position: relative;
    margin: 50px 42px; 
    width: 300px;
    height: 200px;
    background: #060F55;
    border-radius: 100px 0 0 0;
  }
  .g::after {
    position:absolute;
    content: ' ';
    margin: 50px;
    width: 300px;
    height: 200px;
    background: #6592CF;
    border-radius: 50px 0 0 0;
  }
</style>
```