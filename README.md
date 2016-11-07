#To the top in a tweet

![Birds!](img.jpg)

A Simple animated JS scroll-to-the-top-thingamajiggy that fits in a tweet!

```javascript
const ToTheTop=()=>{const w=window,s=setInterval(()=>{let sp=w.scrollY;if(w.scrollY>0)sp-=15,w.scrollTo(0,sp);else clearInterval(s)})}
```
