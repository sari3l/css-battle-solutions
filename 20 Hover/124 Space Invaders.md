# 124 Space Invaders

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16792111286926/16792111327235.png)

## 分析

有一说一，这个后端算法是真的垃圾

## done

```html
<ul>
  <li p><li p><li p><li p>
    <li y><li><li y><li y>
    </ul>
<img><i>
<style>
  * {
    color: #0000;
    margin: var(--m);
    background: var(--b, #071945);
  }
  ul {
    display: flex;
    gap: 40px;
    flex-wrap: wrap; 
    margin: 40 0;
  }
  li {
    width: 50;
    height: 10;
  }
  li::before, li::after {
    content: '';
    position: absolute;
    padding: 5;
    margin: 10 -10;
    background: var(--b);
  }
  li::after{
    margin: 10 50;
  }
  [p] {
    --b: #B069F7;
  }
  [y] {
    --b: #F8DA37;
  }
  img {
    padding: 5;
    --b: #2CE1EA;
    --m: 70 195;
    color: #2CE1EA;
    box-shadow: 0 30px, 0 60px, 0 70px;
  }
  i {
    position: absolute;
    padding: 15;
    --b: #2CE1EA;
    margin: 145 -215;
    transform: rotate(45deg);
  }
</style>
```