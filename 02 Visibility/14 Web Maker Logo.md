# 14 Web Maker Logo

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16772055946062/16772056059412.png)


## 分析

原本想`background + filter + linear-gradient`的，但是drop-shadow不支持渐变，导致底层无法处理

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16772055946062/16772064034102.jpg)

## done

还是做两个上下层

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16772055946062/16772067991666.jpg)

```html
<div></div>
<style>
  * {
    background: #F2F2B6;
  }  
  div::before, div::after {
    content: '';
    position: absolute;
    width: 185px;
    height: 130px;
    transform: skewX(30deg);
    margin: 77 109;
    background: linear-gradient(139deg,#FD4602 0, 45%, transparent 0, 55.5%, #FF6D00 55.5%);
  }
  div::after {
    margin: 77 89;
    background: linear-gradient(139deg,#FF6D00 0, 45%, transparent 0, 55.5%, #FD4602 55.5%);
  }
</style>
```