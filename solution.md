# Digital Clock
## Date and Time Functionality

```JavaScript
let text=document.querySelector('#clock')
let blank=document.querySelector('#date');

setInterval(function(){
    let clock=new Date()
    text.innerHTML=clock.toLocaleTimeString()
    blank.innerHTML=clock.toLocaleDateString()
},1000)

```
