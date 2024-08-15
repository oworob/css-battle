```html
<div>
  <div></div>
</div>
<div class='center'>
  <div></div>
</div>
<div>
  <div></div>
</div>
```

```css
<style>
  body {
    background: #62306D;
    margin: 0 50 auto;
    display: flex;
    align-items: flex-end;
    gap: 10;
  }
  body>div {
    width: 100;
    background: #F7EC7D;
    height: 100;
    &.center {
      height: 200;
      >div {
         background: #AA445F;
        outline: 20px solid #E38F66;
      }
    }
    >div {
      width: 60;
      height: 60;
      margin: auto;
      border-radius: 50%;
      background: #E38F66;
      position: relative;
      bottom: 30;
      outline: 20px solid #AA445F;
    }
  }
</style>
```
