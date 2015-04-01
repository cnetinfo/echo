# echo
js 图片延迟加载库

html
``` html
<div>
    <img  src="images/blank.gif" data-echo="readly.jpg"  />
</div>
```    
   
 css   
 ``` css
<style>
    div img {background: url("loading.gif") no-repeat 50% center;}
</style>
 ``` 
js
 ``` javascript
<script src="echo.min.js"></script>
<script>
Echo.init({
    offset: 0,
    throttle: 0
});
</script>
 ```
