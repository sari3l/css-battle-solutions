# 117 Arineo

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16771435354021/16771536911610.jpg)

## 分析

原本使用polygon到了这一步，然后发现border是在元素上进行的，导致没办法直接在path路径上加白边 

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16771435354021/16771536873362.jpg)

```html
<div></div>
<style>
  div {
    margin: 139px auto;
    height: 22px;
    width: 22px;
    border-radius: 50%;
    background: #0088CA;
    position:relative;
  }
  div::before {
    content: '';
    position: absolute;
    margin: -79 -97;
    background: #2E2926;
    width: 216px;
    height: 180px;
    clip-path: polygon(0 100%, 39% 0, 61% 0, 100% 100%, 79.5% 100%, 50% 24%, 20.5% 100%);
  }
  div::after {
    content: '';
    position: absolute;
    margin: -79 -97;
    width: 250px;
    height: 180px;
    background: #0088CA;
    clip-path: polygon(11.2% 27.5%, 43.2% 72%, 91.2% 5.1%, 91.2% 21%,  43.1% 87.5%, 11.2% 43%);
  }
</style>
```

## done

这里犯傻了一点，将box-shadow的x-offset设置为负，这样右侧就可以留出来进行拼接

```html
<div a><div b></div></div>
<style>
  div[a] {
    margin: 139px auto;
    height: 22px;
    width: 22px;
    border-radius: 50%;
    background: #0088CA;
    position:relative;
  }
  div[a]::before {
    content: '';
    position: absolute;
    margin: -79 -97;
    background: #2E2926;
    width: 216px;
    height: 180px;
    clip-path: polygon(0 100%, 39% 0, 61% 0, 100% 100%, 79.5% 100%, 50% 24%, 20.5% 100%);
  }
  div[b]::after,div[b]::before  {
    content: '';
    position: fixed;
    top: 149;
    left: 120;
    width: 80;
    height: 29;
    transform:skewY(45deg);
    background: #0088CA;
    box-shadow: -30px 0 0 11px #FFFFFF;
  }
  div[b]::before {
    top: 129;
    left: 200;
    width: 120;
    transform:skewY(-45deg);
  }
</style>
```