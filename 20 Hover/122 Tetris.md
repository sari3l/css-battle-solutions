# 122 Tetris

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16792093800015/16792093876202.png)

## 分析

后端什么乱七八糟的对比算法，使用padding就不能满分

## done

```html
<ul>
  <li><li><li><li><li r><li>
  <li><li><li><li r><li r><li>
  <li y><li y><li><li r><li><li>
  <li y><li y><li r><li><li p><li>
  <li r><li r><li r><li c><li p><li p>
  <li y><li c><li c><li c><li p><li c>
<style>
  * {
    color: #0000;
    background: var(--b, #173889);
  }
  ul {
    display: flex;
    gap: 6px;
    flex-wrap: wrap; 
    margin: -8 0 0 2;
  }
  li {
    width: 45;
    height: 45;
  }
  [r] {
    --b: #EE4F63;
  }
  [y] {
    --b: #F8DA37;
  }
  [c] {
    --b: #2CE1EA;
  }
  [p] {
    --b: #B069F7;
  }
</style>
```