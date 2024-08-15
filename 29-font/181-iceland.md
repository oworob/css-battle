```html
<div class='hor'></div>
<div class='ver'></div>
<div class='ver bot'></div>
```

```css
<style>
  body {
    background: #33499F;
    margin: 0;
  }
  div {
    background: #DE3832;
    outline: 15px solid #FFFFFF;
  }
  .hor {
    width: 100%;
    height: 50px;
    margin: 125px auto;
  }
  .ver {
    position: absolute;
    bottom: 175px;
    left: 110px;
    height: 100%;
    width: 50px;
    outline: none;
    border: solid #FFFFFF;
    border-width: 0 15px 0 15px;
    &.bot {
     bottom: -175px; 
    }
  }
</style>
```
