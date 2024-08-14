```html
<div class='container'>
  <div class='top'></div>
  <div class='bottom'></div>
  <div class='middle-bar'></div>
  <div class='middle'></div>
</div>
```

```css
<style>
  html {
    background: #6CB3A9;
  }
  .container {
    margin: 60px auto;
    width: 200px;
    position: relative;
  }
  .middle-bar {
    position: absolute;
    top: 80px;
    border-right: 10px solid #6CB3A9;
    border-left: 10px solid #6CB3A9;
    background: #781728;
    height:20px;
    width: 180px;
    z-index: 1;
  }
  .middle {
    height: 50px;
    width: 50px;
    border-radius: 50%;
    background: #F6DF96;
    z-index: 2;
    position: absolute;
    top: 65px;
    left: 75px;
    outline: 10px solid #781728;
    
  }
  .top, .bottom {
    position: absolute;
    top: -10px;
    background: #D25B70;
    width: 200px;
    height: 100px;
    border-radius: 50% 50% 0 0 / 100% 100% 0 0;
  }
  .bottom {
    rotate: 180deg;
    top: 90px;
    background: #FFFFFF;
  }
</style>
```
