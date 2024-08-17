```html
<div class='head'></div>
<div class='eye'></div>
<div class='top'></div>
<div class='lbot'></div>
<div class='rbot'></div>
<div class='mid'></div>
```

```css
<style>
  body {
    background: #232323;
  }
  .head {
    position: absolute;
    top: 34;
    left: 120;
    width: 160;
    height: 215;
    border-radius: 100px 100px 0 0;
    background: #AF3A3A;
  }
  .eye {
    width: 120;
    left: 140;
    top: 87;
    height: 70;
    position: absolute;
    background: #232323;
    border-radius:90%;
  }
  .top {
    width: 80;
    left: 160;
    top: 52;
    height: 50;
    position: absolute;
    background: #AF3A3A;
    border-radius: 90%;
  }
  .lbot, .rbot {
    width: 45;
    left: 129;
    top: 213;
    height: 50;
    position: absolute;
    background: #AF3A3A;
    rotate: 30deg;
  }
  .rbot {
    rotate: -30deg;
    top: 213;
    left: 226;
  }
  .mid {
    position: absolute;
    left: 165;
    width:70;
    top: 120;
    height: 129;
    background: #232323;
  }
</style>
```
