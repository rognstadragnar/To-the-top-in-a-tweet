#To the top in a tweet!
####A Simple JS scroll-to-the-top-thingamajiggy

```javascript
const ToTheTop=()=>{const w=window,s=setInterval(()=>{let sp=w.scrollY;if (w.scrollY > 0)sp-=15,w.scrollTo(0, sp);else clearInterval(s)})}
```
