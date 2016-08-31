

|      属性     |     含义      |      初始值     |    重要性      |
| ------------- |:-------------:| ------------- |:-------------:|
| whatToType     |放大的图片框id |  无     |必须 | 



##调用示例：
```javascript
<div class="page">
    <h1>Smooth Products</h1>
	<div class="sp-loading"><img src="images/sp-loading.gif" alt=""><br>LOADING IMAGES</div>
	<div class="sp-wrap">
		<a href="images/1.jpg"><img src="images/1_tb.jpg" alt=""></a>
		<a href="images/2.jpg"><img src="images/2_tb.jpg" alt=""></a>
		<a href="images/3.jpg"><img src="images/3_tb.jpg" alt=""></a>
		<a href="images/4.jpg"><img src="images/4_tb.jpg" alt=""></a>
		<a href="images/5.jpg"><img src="images/5_tb.jpg" alt=""></a>
		<a href="images/6.jpg"><img src="images/6_tb.jpg" alt=""></a>
	</div>

</div>

<script src="js/jquery.min.js" type="text/javascript"></script>
<script type="text/javascript" src="js/smoothproducts.min.js"></script>
<script type="text/javascript">
    /* wait for images to load */
    $(window).load(function() {
    	$('.sp-wrap').smoothproducts();
    });
</script>
```
##效果演示：
![mahua](http://myweb-10017157.file.myqcloud.com/gif/131171287495094341.gif)
