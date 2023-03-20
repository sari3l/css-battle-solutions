# 9 Tesseract

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16772288546212/16772288665754.png)

## done

好像没有啥比较简单的写法

```html
<div></div>
<style>
   *{
     background: #222730;
     margin: 0
}
  div {
    position: absolute;
    top: 25%;
    width: 100%;
    height: 50%;
    background: #4CAAB3;
  }
  div::before{
    content: ' ';
    position: absolute;
    left: 125;
    width: 150;
    height: 150;
    transform:rotate(45deg);
    background: #4CAAB3;
    box-shadow: 0 0 0 50px #222730 
  }
  div::after{
    content: ' ';
    position: absolute;
    top: 33.5%;
    left: 175;
    width: 50;
    height: 50;
    border-radius: 50%;
    background: #393E46;
  }
</style>
```