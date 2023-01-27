<template>
<div class="box4">
	<p class="msg1">产业布局</p>
	<div class="top"><img src="../../assets/images/未标题-1.png" alt="">
	<p class="msg2"></p>
	</div>
	<div class="content">
		<div class="list active">
			<img src="./images/未标题-1.png" alt="">
			<p class="title">机加工</p>
			<p class="msg">宇辉电子加密各种精密五金冲压件拉伸件及精...</p>
		</div>
		<div class="list">
			<img src="./images/未标题-2.png" alt="">
			<p class="title">3D打印</p>
			<p class="msg">宇辉电子采用进口3d打印设备,支持高进度,多...</p>
		</div>
		<div class="list">
			<img src="./images/未标题-3.png" alt="">
			<p class="title">产品热处理</p>
			<p class="msg">宇辉电子拥有先进的热处理设备,广受用户好评...</p>
		</div>
		<div class="list">
			<img src="./images/未标题-4.png" alt="">
			<p class="title">模具预加热</p>
			<p class="msg">宇辉电子模具热处理是为了提升模具的精密度...</p>
		</div>
		<div class="list">
			<img src="./images/未标题-5.png" alt="">
			<p class="title">模具研发设计</p>
			<p class="msg">宇辉电子从事模具的数字化设计,包括型腔模与冷...</p>
		</div>
	</div>
</div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
.box4{
	position: relative;
	width: 1920px;
	height: 610px;
	box-shadow: 0px 1px 10px #d6cdcd;
	
}
.content{
	position: absolute;
	width: 1330px;
	height: 600px;
	top: 50%;
	left: 50%;
	margin-top: -300px;
	margin-left: -665px;
	display: flex;
}
.list{
	text-align: center;
	width: 266px;
	height: 600px;
}
.msg{
	width: 160px;
	margin-left: 53px;
	font-size: 14px;
	color: #8d8d8d;
}
img{
	margin-top: 204px;
}
.title{
	font-size: 18px;
	color: #353535;
}
.top{
	position: absolute;
	margin-top: -210px;
	left: 50%;
	margin-left: -246px;
}
.msg1{
	position: absolute;
	margin-top: -73px;
	font-size: 26px;
	left: 50%;
	margin-left: -300px;
	color: #353535;
}
</style>