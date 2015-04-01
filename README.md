# echo
js 图片延迟加载库

html
<div>
    <img  src="images/blank.gif" data-echo="readly.jpg"  />
</div>
   
   
 css                   
<style>
    div img {background: url("loading.gif") no-repeat 50% center;}
</style>

js
<script src="echo.min.js"></script>
<script>
Echo.init({
    offset: 0,
    throttle: 0
});
</script>
