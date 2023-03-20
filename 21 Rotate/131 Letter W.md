# 131 Letter W

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16771330139947/16771336890043.jpg)

## 分析

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16771330139947/16771336707255.jpg)

作为三部分处理然后投阴影

```html
<div></div>
<style>
  * {
    background: #E38F66;
  }
  div {
    margin: 70 87;
    width: 30;
    height: 100;
    border-radius: 1in 1in 0 0;
    background: #62306D;
    box-shadow: 90px 0 #62306D, 180px 0 #FFFBDA;
    position: relative;
  }
   div::before {
    content: '';
    margin: 100 0;
    position: absolute;
    width: 120;
    height: 60;
    border-radius: 0 0 1in 1in;
    background: #62306D;
    box-shadow: 90px 0 #FFFBDA;
  }
  div::after {
    content: '';
    margin: 100 30;
    position: absolute;
    width: 60;
    height: 30;
    background: #E38F66;
    border-radius: 0 0 1in 1in;
    box-shadow: 90px 0 #E38F66;
  }
</style>
```

然后看到了大佬的无情写法，既然都用box-shadow了，为啥不用到底！

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16771330139947/16771346398296.jpg)

通过构造一个原始图形（红椭圆），然后4个蓝色增量，1个红色减量来构造一个U型

```html
<div></div>
<style>
  * {
    background: #E38F66;
  }
  div::after, div::before {
    content: ' ';
    position: absolute;
    margin: 0 207;
    width: 60;
    height: 130;
    border-radius: 30px;
    color: #FFFBDA;
    box-shadow:
      -45px 47px 0 -15px,
      45px 47px 0 -15px,
      0 62px #E38F66,
      0 0 0 30px #E38F66,
      0 62px 0 30px;
  }
  div::after {
    margin: 0 117;
    color: #62306D;
  }
</style>
```

实际这里又有一个坑（是真的多），伪类总会莫名其妙有个边缘显示

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16771330139947/16771366963173.jpg)

解决方式就是换成元素...

## done

这里注意margin，`0 -357`对应控制左边的图形，`0 207`对应控制右边

```html
<img/><img/>
<style>
  * {
    background: #E38F66;
  }
  img {
    margin: 0 -357 0 207;
    padding: 60 30;
    border-radius: 1in;
    color: #FFFBDA;
    box-shadow:
      -45px 47px 0 -15px,
      45px 47px 0 -15px,
      0 72px #E38F66,
      0 0 0 30px #E38F66,
      0 72px 0 30px;
  }
  img+img {
    color: #62306D
  }
</style>
```