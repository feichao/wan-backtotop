#wan-backtotop,  a jQuery Back-to-top
----------

> ![demo](http://7xl1b4.com1.z0.glb.clouddn.com/wan-backtotop.png)

### [demo](http://blog.0xfc.cn/2015/08/24/backtotop/) ###

> demo/demo.html

**prepare to use**
> - include jQuery
> - include src/wan-backtotop.js
> - in your html:
> ```html
> <div class="wan-backtotop"></div>
> ```

**how to use**
 

> `$(".wan-backtotop").WanBackToTop();`

**options**

> imgSrc: string，the path of the back-to-top image
> 
> displayTop: number，how far away from the top to display back-to-top btn
> 
> speed: number，the duration back to top
> 
> size: object，{height, width}，the size of the back-to-top image
> 
> position: object，{right, bottom}，the position of the back-to-top image
> 
> template: useless