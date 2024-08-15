```html
<div class='ball top'></div>
<div class='ball left'></div>
<div class='ball right'></div>
<div class='triangle'></div>
<div class='triangle small'></div>
```

```css
<style>
  body {
    background: #F0CD48;
  }
  .ball {
    position: absolute;
    width: 100px;
    height: 100px;
    background: #66284A;
    border-radius: 50%
  }
  .top {
    top: 30px;
    left: 150px;
  }
  .left {
    top: 170px;
    left: 50px;
  }
  .right {
    top: 170px;
    left: 250px;
  }
  .triangle {
    position: absolute;
    top: 80px;
    left: 100px;
    border-left: 100px solid transparent;
	border-right: 100px solid transparent;
	border-bottom: 140px solid #F0CD48;
  }
  .small {
    top: 105px;
    left: 130px;
    border-left: 70px solid transparent;
	border-right: 70px solid transparent;
	border-bottom: 100px solid #66284A;
  }
</style>
```
