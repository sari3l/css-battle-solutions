# 57 Pillars

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16775120536492/16775120608269.png)

## 分析

总感觉能用margin直接排布

## done

```html
<o>
<style>
  * {
    background: #191919;
  }
  o, o::after {
    position: absolute;
    content: '';
    background: #4F77FF;
    padding: 55;
    margin: 87 137
  }
  o::after {
    margin: -75 -75;
    padding: 15;
    border-radius: 50%;
    box-shadow: 0 120px #4F77FF, 7.5px 7.5px 0 7.5px #F9E492, 7.5px 112.5px 0 7.5px #F9E492, 15px 15px 0 15px #191919, 15px 105px 0 15px #191919;
    -webkit-box-reflect: right 90px;
  }
</style>
```