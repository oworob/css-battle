```html
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
```

```css
<style>
  body {
    margin: 0 auto;
    padding: 10;
    background: #5C434C;
    display: grid;
    grid-template-columns: 1fr 1fr 1fr 1fr 1fr;
    gap: 20px
  }
  div {
    border-top-left-radius: 100%;
    width: 80;
    height: 80;
    background: #F09462;
    &:nth-child(2n) {
      background: #F5D6B4;
    }
  }
</style>
```
