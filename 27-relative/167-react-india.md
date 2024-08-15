```html
<div class='ring white'></div>
<div class='ring green'></div>
<div class='ring orange'></div>
<div class='dot'></div>
```

```css
<style>
  body {
    background: #0D1335;
  }
  .ring {
    position: absolute;
    left: 85px;
    top: 105px;
    width: 230px;
    height: 90px;
    border-radius: 50%;
  }
  .white {
    outline: 10px solid #FBFAE2;
  }
  .orange {
    rotate: 60deg;
    outline: 10px solid #DC6638;
  }
  .green {
    rotate: 120deg;
    outline: 10px solid #4FA07B;
  }
  .dot {
    margin: 130px auto;
    width: 40px;
    height: 40px;
    border-radius: 50%;
    background: #73C6EA;
  }
</style>
```
