# 4 Ups n Downs

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16772266077120/16772266213496.png)


这个比较讨厌，rotate会将原元素旋转，导致shadow也同样转动

## done

```html
<div></div>
<style>
  * {
    background: #62306D;
  }
  div {
    position: absolute;
    top: 150;
    left: 50;
    width: 100;
    height: 100;
    border-radius: 0 0 50px 50px;
    background: #F7EC7D;
    box-shadow: 200px 0 #F7EC7D;
    transform: rotate(180)
  }
  div::before {
    content: '';
    position:absolute;
    top: -100;
    left: 100;
    width: 100;
    height: 100;
    border-radius: 50px 50px 0 0;
    background: #F7EC7D;
  }
</style>
```