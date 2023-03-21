# 15 Overlap

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16772068195858/16772068327586.png)

以为这两个色能够产出中间部分，试了各种blend，结果。。。题目阐明了是overlay，需要处理overflow

## done

```html
<div></div>
<style>
  * {
    background: #09042A;
  }  
  div, div::before {
    position: absolute;
    top: 25%;
    left: 18.8%;
    background: #7B3F61;
    width: 150;
    height: 150;
    border-radius: 50%;
    box-shadow: 100px 0 0 #E78481;
    overflow:hidden;
  }
  div::before{
    content: '';
    top: 0;
    left: 66.5%;
    background: #09042A;
  }
</style>
```