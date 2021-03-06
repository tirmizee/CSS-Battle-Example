# CSS-Battle-Example

### Ex.1 https://cssbattle.dev/play/1

```html

<div></div>

```

```css

<style>
  body {
    background: #5d3a3a;
  }
  div {
    width: 200px;
    height: 200px;
    background: #b5e0ba;
    position : relative;
    top : -8px;
    left : -9px;
  }
</style>

```

### Ex.2 https://cssbattle.dev/play/2

```html
<div></div>
<div></div>
<div></div>
<div></div>
```

```css
<style>
  body {
    background: #62374e;
  }
  div {
    width: 50px;
    height: 50px;
    background: #fdc57b;
    position :absolute;
  }
  div:nth-child(1) {
    top : 50px;
    left : 50px
 
  }
  div:nth-child(2) {
    top : 50px;
    right : 50px
  }
  div:nth-child(3) {
    top : 200px;
    right : 50px
  }
   div:nth-child(4) {
    top : 200px;
    right : 300px
  }

</style>
```

### Ex.3 https://cssbattle.dev/play/3

```html
<div a>
<div b>
<div c>
<div d>
```

```css
<style>
  body {
    background:#6592CF;
    margin:0;
  }
  
  div[a] {
    width: calc(100% - 100px);
    height: 150px;
    background: #243D83;
    position: absolute;
    left : 50%;
    top : 50%;
    transform:translate(-50%,-50%);
  }
  
   div[b] {
    width: 250px;
    height: 250px;
    border-radius:175px;
    background: #6592CF;
    position: absolute;
    left : 50%;
    top : 50%;
    transform:translate(-50%,-50%);
  }
  
  div[c] {
    width: 150px;
    height: 150px;
    border-radius:75px;
    background: #243D83;
    position: relative;
    left : 50%;
    top : 50%;
    transform:translate(-50%,-50%);
  }
  
  div[d] {
    width: 50px;
    height: 50px;
    border-radius:25px;
    background: #EEB850;
    position: absolute;
    left : 50%;
    top : 50%;
    transform:translate(-50%,-50%);
  }
  
</style>

```


### Ex.4 https://cssbattle.dev/play/4

```html
  <div></div>
  <div></div>
  <div></div>
```
```css
<style>
  body {
    background:#62306D;
    display: flex;
    align-items:center;
    justify-content:center;
  }
  
  div:nth-child(1){
    width: 100px;
    height: 100px;
    background:#F7EC7D;
    border-radius:0px 0px 50px 50px;
    margin-top:100px;
  }
  
  div:nth-child(2){
    width: 100px;
    height: 100px;
    background:#F7EC7D;
    border-radius:50px 50px 0px 0px;
    margin-top:-100px;
  }
  
  div:nth-child(3){
    width: 100px;
    height: 100px;
    background:#F7EC7D;
    border-radius:0px 0px 50px 50px;
    margin-top:100px;
  }
  
</style>
```

### Ex.5 https://cssbattle.dev/play/5

```html
  <div></div>
  <div></div>
  <div></div>
```
```css
<style>
  body {
    background:#0B2429;
    display:flex;
    justify-content:center;
    
  }
  div:nth-child(1){
    width: 120px;
    height: 120px;
    background:#F3AC3C;
    border-radius:50% 0px 50% 50%;
    margin-top:82px;
    transform:translate(50%,50%);
    z-index:2;
  }
  div:nth-child(2){
    width: 120px;
    height: 120px;
    background:#998235;
    border-radius:50% 0px 50% 50%;
    margin-top:82px;
    z-index:1
  }
  div:nth-child(3){
    width: 120px;
    height: 120px;
    background:#F3AC3C;
    border-radius:60px 60px 60px 60px;
    margin-top:82px;
    transform:translate(-50%,-50%);
  }
</style>
```

### Ex.6 https://cssbattle.dev/play/6

```html
<div></div>
```
```css
<style>
  body {
    background:#E3516E;
    display:flex;
    justify-content:center;
    align-items:center;
  }
  div:nth-child(1){
    width: 200px;
    height: 200px;
    background: conic-gradient(#FADE8B 0% 25%, #E3516E 25% 50%, #F7F3D7 50% 75%, #51B5A9 75% 100%);
    border-radius:50% 50% 50% 50%;
    position: absolute;
  }
</style>
```

### Ex.7 https://cssbattle.dev/play/7

```html
  <div></div>
  <div></div>
  <div></div>
```
```css
<style>
  body {
    background:#0B2429;
    display:flex;
    justify-content:center;
    align-items:center;
    margin:0;
  }
  div {
    position: relative;
    border-radius:65% 0% 65% 0%;
    width: 150px;
    height: 150px;
  }
  div:nth-child(1){
    background: #1A4341;
    left:25px;
    
  }
  div:nth-child(2){
    background: #998235;
    position: absolute;
  }
  div:nth-child(3){
    background: #F3AC3C;
    left:-25px;
  }
</style>

```


### Ex.8 https://cssbattle.dev/play/8

```html
  <div odd></div>
  <div event></div>
  <div odd></div>
  <div event></div>
  <div odd></div>
  <div event></div>
  <div odd></div>
  <div></div>
  <div></div>
  <div></div>
```
```css
<style>
  body {
    background:#6592CF;
    display:flex;
    justify-content:center;
    align-items:center;
    margin:0;
  }
  div[odd]{
    background: #060F55;
    width:20px;
    height:130px;
    position: relative;
    border-radius:20px;
    top:-35px
  }
  div[event]{
    background: #6592CF;
    width:20px;
    height:100px;
    position: relative;
    border-radius:20px;
    z-index:1;
    top:-40px
  }
  div:nth-child(8){
    width:140px;
    height:140px;
    border-radius:50%;
    position:absolute;
    background: #060F55;
    bottom:50px;
    z-index:0;
  }
  div:nth-child(9){
    background:#060F55;
    width:20px;
    height:130px;
    position: absolute;
    top : 200px;
    z-index : 1;
  }
</style>
```

### Ex.9 https://cssbattle.dev/play/9

```html
  <div></div>
  <div></div>
  <div></div>
  <div></div>
```
```css
<style>
  body {
    background:#222730;
    display:flex;
    justify-content:center;
    align-items:center;
    margin:0;
  }
  div:nth-child(1){
    background:#4CAAB3;
    height:150px;
	width : 100%
  }
  div:nth-child(2){
    background: #222730;
    height:250px;
    width:250px;
    transform: rotate(45deg);
    position: absolute;
  }
  div:nth-child(3){
    background: #4CAAB3;
    height:150px;
    width:150px;
    transform: rotate(45deg);
    position: absolute;
  }
  div:nth-child(4){
    background: #393E46;
    height:50px;
    width:50px;
    position: absolute;
    border-radius:50%;
  }

</style>
```

### Ex.10 https://cssbattle.dev/play/10

```html
  <div m></div>
  <div m></div>
  <div m></div>
  <div o></div>
  <div i></div>
  <div o></div>
  <div i></div>
  <div o></div>
  <div i></div>
```
```css
<style>
  body {
    background:#62306D;
    display:flex;
    justify-content:center;
    align-items:center;
    margin:0;
  }
  div[m] {
    background:#F7EC7D;
    width: 100px;
    border-radius:50px;
    position: relative;
    z-index:0;
  }
  div[o] {
    width: 100px;
    height: 100px;
    border-radius:50%;
    position: absolute;
    z-index:1;
  }
  div[i] {
    width: 60px;
    height: 60px;
    border-radius:50%;
    position: absolute;
    z-index:1;
  }
  div:nth-child(1){
    height: 200px;
    top : 100px;
  }
  div:nth-child(2){
    height: 300px;
    top : 50px;
  }
  div:nth-child(3){
    height: 200px;
    top : 100px;
  }
  div:nth-child(4){
    background:#E38F66;
    top:50px;
  }
  div:nth-child(5){
    background:#AA445F;
    top:70px;
  }
  div:nth-child(6){
    background:#AA445F;
    top : 150px;
    left : 50px;
  }
  div:nth-child(7){
    background:#E38F66;
    top : 170px;
    left : 70px;
  } 
  div:nth-child(8){
    background:#AA445F;
    top : 150px;
    left : 250px;
  }
  div:nth-child(9){
    background:#E38F66;
    top : 170px;
    left : 270px;
  }
</style>
```


### Reference

- https://dzone.com/articles/css-position-relative-vs-position-absolute#:~:text=Relative%20%2D%20the%20element%20is%20positioned,on%20the%20user's%20scroll%20position.
