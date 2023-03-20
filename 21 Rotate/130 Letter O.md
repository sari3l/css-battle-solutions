# 130 Letter O

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16771319390440/16771326287865.jpg)


## 分析

使用box-shadow的话，即使transparent也没法直接获取交错的这部分内容，虽然可以修补，但是会麻烦一点

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16771319390440/16771326240778.jpg)

这里使用filter下的drop-shadow来构造阴影，这里就提到`盒阴影`与`阴影`的区别（简单的说，盒子不透光）

## done

```html
<div></div>
<style>
  * {
    background: #926927;
  }
  div {
    margin: 70 152;
    width: 60px;
    height: 120px;
    border: 20px solid white;
    border-radius: 30px;
    background: transparent;
    filter: drop-shadow(-20px 0px #6D480A);
  }
</style>
```

## 参考资料

1. [CSS3 filter:drop-shadow滤镜与box-shadow区别应用](https://www.zhangxinxu.com/wordpress/2016/05/css3-filter-drop-shadow-vs-box-shadow/)