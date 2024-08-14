```html
<div class='bc'>
  <div class='left'></div>
  <div class='middle'></div>
  <div class='right'></div>
</div>
```
```css
<style>
  html {
    background: #F3AC3C
  }
  .bc {
    width: 168px;
    height: 168px;
    background: #000000;
    border-radius: 50%;
    margin: 70px auto;
    outline: 16px solid #9F3333;
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 70px;
    .middle {
      position: absolute;
      background: #9F3333;
      height: 180px;
      width: 36px;
    }
    .left, .right {
      position: relative;
      bottom: 5px;
      background: #FFFFFF;
      border-radius: 50% 50% 0 0/100% 100% 0 0;
      width: 30px;
      height: 15px;
    }
    .left {
      rotate: -152deg;
    }
    .right {
      rotate: 152deg;
    }
  }
</style>
```
