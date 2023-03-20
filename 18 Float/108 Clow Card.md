# 108 Clow Card

![](https://raw.githubusercontent.com/sari3l/css_battle/main/media/16792291940142/16792292057588.png)

## done

```html
<p></p><i></i>
<style>
  *, :before, :after{
    content: '';
    position: absolute;
    margin: var(--m);
    padding: var(--p);
    border-radius: var(--r);
    background: var(--b, #000);
  }
  p {
    --p: 75 150;
    --b: linear-gradient(-75deg, #E96A23 36.3%, #EBAE11 0 44%, #E96A23 0 48.2%, #EBAE11 0 63.3%, #E96A23 0);
    --m: 75 50;
  }
  p::before, p::after {
    --p: 60 120;
    --b: #000;
    --m: -60 -120;
    --r: 12px;
  }
  p::after {
    --p: 45 135;
    --m: -45 -135;
  }
  i {
    --p: 25;
    --b: #EBAE11;
    --r: 50%;
    --m: 125 175; 
  }
  i::before, i::after {
    --p: 30 60;
    --m: -35 -65;
    --b: #0000;
    border: 5px solid #EBAE11;
  }
  i::after {
    --p: 40 100;
    --m: -45 -105;
  }
</style>
```