# 6 Missing Slice

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16772276078428/16772276145736.png)

## 分析

开始想用overflow做的，结果想起来大神的border操作，直接对应四个方向

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16772276078428/16772288437125.jpg)

## done

```html
<div></div>
<style>
 body{
   background: #E3516E;
   display: flex;
   justify-content: center;
   align-items: center;
 }  
  div {
    border: 100px solid;
    border-radius: 50%;
    border-color:#FADE8B transparent #F7F3D7 #51B5A9;
    transform: rotate(45deg);
  }
</style>
```