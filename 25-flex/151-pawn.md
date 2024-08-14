```html
<div class='container'>
  <div class='one'></div>
  <div class='two'></div>
  <div class='three'>
    <div class='left'></div>
    <div class='right'></div>
  </div>
  <div class='four'></div>
</div>
```

```css
<style>
  html {
    background: #F5D6B4
  }
  .container {
    margin: 55px auto;
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 5px;
    >div {
      background: #D86F45;
    }
    .one {
      width: 50px;
      height: 50px;
      border-radius: 50%;
    }
    .two {
      width: 80px;
      height: 20px;
      border-radius: 10px 10px 20px 20px
    }
    .three {
      height: 65px;
      width: 90px;
      overflow: hidden;
      .left, .right {
        position: relative;
        left: 65px;
        top: -280px;
        background: #F5D6B4;
        height: 190px;
        width: 200px;
        border-radius: 50%;
      }
       .left {
          left: -175px;
          top: -90px;
        }
      }
    }
  .four {
      width: 140px;
      height: 40px;
      border-radius: 20px 20px 10px 10px
    }
  }
</style>
```
