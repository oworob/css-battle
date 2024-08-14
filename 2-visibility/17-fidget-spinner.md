```html
<div class='ball left'></div>
<div class='ball right'></div>
<div class='bar'></div>
<div class='ball top'></div>
<div class='ball bottom'></div>
```

```css
<style>
  html {
    background: #09042A;
  }
  .ball {
    position: absolute;
    margin: 120px auto;
    width: 60px;
    height: 60px;
    border-radius: 50px;
   
    top: 0;
    &.left {
      left: 110px;
      background: #09042A;
      outline: 10px solid #E78481;
    }
    &.right {
      right: 110px;
       background: #09042A;
      outline: 10px solid #E78481;
    }
    &.top {
      top: -53px;
      right: 170px;
      background: #F5BB9C;
      outline: 11px solid #09042A;
    }
     &.bottom {
      top: 53px;
      right: 170px;
      background: #F5BB9C;
      outline: 11px solid #09042A;
    }
  }
  .bar {
      margin: 130px auto;
      width: 100px;
      height: 50px;
      background: #E78481;
    }
</style>
```
