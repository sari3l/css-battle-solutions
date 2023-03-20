# 139 Lamp

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16770558376115/16770558448357.jpg)

用伪元素实现很丑陋，感觉grid\flex可能更好些

## done

```html
<div></div>
<style>
 * {
   background: #E38F66;
  }  
  div::before {
    content: '';
    position:absolute;
    margin: 82px 127px;
    width: 130px;
    height: 120px;
    clip-path: polygon(26% 0%, 74% 0, 99% 100%, 1% 100%);
    background: #FFFBDA;
  }
  div::after {
    content: '';
    position:absolute;
    margin: 202px 187px;
    width: 10px;
    height: 90px;
    background: #62306D;
  }
</style>
```

```html
<div id='a'></div>
<div id='b'></div>
<style>
  body {
   background: #E38F66;
   display:flex;
    flex-direction: column;
    justify-content:center;
    align-items: center;
    padding-top: 82px;
  }  
  #a{
     width: 130px;
    height: 120px;
    clip-path: polygon(26% 0%, 74% 0, 99% 100%, 1% 100%);
    background: #FFFBDA;
  }
  #b{
    width: 10px;
    height: 90px;
    background: #62306D;
  }
</style>
```