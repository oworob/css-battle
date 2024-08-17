```html
<div class='head'></div>
<div class='mouth'></div>
<div class='ljaw'></div>
<div class='rjaw'></div>
<div class='ljaw'></div>
<div class='leye'></div>
<div class='reye'></div>
<div class='nose'></div>
```

```css
<style>
  body {
    background: #CAE5DC;
  }
  .head {
    margin: 40 auto;
    width: 140;
    height: 140;
    border-radius: 50%;
    background: #000000;
  }
  .mouth {
    position: absolute;
    width: 100;
    height: 50;
    background: #000000;
    left: 150;
    top: 130;
  }
  .ljaw, .rjaw {
    position: absolute;
    width: 4;
    height: 93;
    background: #CAE5DC;
    left: 162;
    top: 180;
    border-left: 16px solid #000000;
    border-right: 16px solid #000000;
  }
  .rjaw {
    left: 202;
  }
  .leye, .reye {
    position: absolute;
    border-radius: 50% 50% 0 0/100% 100% 0 0;
    width: 46;
    height: 23;
    background: #CAE5DC;
    left: 139;
    top: 119;
    rotate: 208deg
  }
  .reye {
    left: 215;
    rotate: 152deg;
  }
  .nose {
    position: absolute;
    border-left: 10px solid transparent;
    border-right: 10px solid transparent;
    border-bottom: 31px solid #CAE5DC;
    left: 190;
    top: 135;
  }
</style>
```
