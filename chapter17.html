<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8" />
<title>事件捕获和冒泡</title>
<style type="text/css">
	html,body{
		width:100%;
		height: 100%;
	}
	#outer{
		width:80%;
		height:80%;
		background-color: #000;
	}
	#mid{
		width:60%;
		height:60%;
		margin:5% auto;
		background-color: #666;
	}
	#inner{
		width:40%;
		height:40%;
		margin:5% auto;
		background-color: #eee;
	}

</style>
</head>
<body>
<div id="outer">
	<div id="mid">
		<div id="inner"></div> 
	</div>
</div>




<script type="text/javascript">	
window.onload = function (){
	var $outer = document.getElementById('outer');
	var $mid = document.getElementById('mid');
	var $inner = document.getElementById('inner');



	$inner.onclick = function(){
		console.log('onclick me ');
	}
	$inner.onclick = function(){
		console.log('onclick me 2');  // 使用相同的属性只调用一次
	}



	$outer.addEventListener("click",function(){  //冒泡阶段，相对目标的父节点 false
		console.log("outer,冒泡");
	},false)
	$mid.addEventListener("click",function(event){
		console.log("mid,冒泡");
		event.stopPropagation();
	},false)
	$inner.addEventListener("click",function(event){
		console.log("inner,目标阶段");   //目标阶段，无所谓捕获还是冒泡。依照顺充执行。
	})
	$inner.addEventListener("click",function(event){
		console.log("inner,目标阶段2");   // 用addEventListener多次调用，会多次执行。
	})
	$outer.addEventListener("click",function(){   //捕获阶段，相对目标的父节点  true
		console.log("outer,捕获");
	},true)
	$mid.addEventListener("click",function(){
		console.log("mid,捕获");
	},true)
	$inner.addEventListener("mouseup",function(){
		console.log("mouseup");
	})
	$inner.addEventListener("mousedown",function(){
		console.log("mousedown");

	},true)
	$inner.addEventListener("dblclick",function(){
		console.log("dblclick");
	},true)



}



</script>

</body>
</html>

