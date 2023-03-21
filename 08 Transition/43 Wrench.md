# 43 Wrench

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16774669801442/16774669874591.png)

## 分析

咋说呢，要习惯用overflow，满脑子的shadow、border可不行

## done

```html
<div></div>
<style>
  * {
    background: #6592CF;
  }
  div {
    position: absolute;
    margin: -10 137;
    width: 110;
    height: 300;
    overflow: hidden;
  }
  div::after {
    content: '';
    position: absolute;
    margin: 32 40;
    height: 182;
    width: 150;
    border: 30px solid #243D83;
    border-radius: 70px;
    -webkit-box-reflect: left -30px;
  }
</style>
```