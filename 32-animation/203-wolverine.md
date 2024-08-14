```html
<div class='head'></div>
<div class='neck'></div>
<div class='jaw'></div>
<div class='rear'></div>
<div class='lear'></div>
<div class='mouth'></div>
<div class='leye'></div>
<div class='reye'></div>
```
```css
<style>
  html {
    background: #373794;
  }
  div {
    position: absolute;
  }
  .head {
    top: 87px;
    left: 155px;
    border-radius: 50%;
    background: #F3AC3C;
    width: 90px;
    height: 90px;
  }
  .neck {
    top: 170px;
    left: 160px;
    border-radius: 0 0 50% 50%/0 0 100% 100%;
    background: #0E0E39;
    width: 80px;
    height: 50px
  }
  .jaw {
    top: 170px;
    left: 173px;
    border-radius: 0 0 55% 55%/0 0 50% 50%;
    background: #F3AC3C;
    width: 54px;
    height: 58px
  }
  .rear{
    top: 107px;
    left: 200px;
    border-radius: 50px 0 70px 0;
    background: #0E0E39;
    width: 100px;
    height: 70px
  }
  .lear {
    top: 107px;
    right: 200px;
    border-radius: 0 50px 0 70px;
    background: #0E0E39;
    width: 100px;
    height: 70px
  }
  .mouth {
    top: 190px;
    right: 180px;
    border-radius: 20px;
    background: #FFFFFF;
    width: 40px;
    height: 20px
  }
  .leye {
    top: 146px;
    right: 205px;
    background: #FFFFFF;
    width: 30px;
    height: 20px;
    border-radius: 0 70px 0 70px;
  }
  .reye {
    top: 146px;
    left: 205px;
    background: #FFFFFF;
    width: 30px;
    height: 20px;
    border-radius: 70px 0 70px 0;
  }
</style>
```
