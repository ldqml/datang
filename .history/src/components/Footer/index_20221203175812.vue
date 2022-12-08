<template>
<div class="box1">
	<div class="top">
		<span class="top-1"><img src="./images/未标题-3.png" alt=""></span>
		<span class="top-2"><img src="./images/wx1.png" alt=""></span>
	</div>
	<div class="content">
		<div class="content-1">
			<p>服务赢得口碑，品质赢得品牌</p>
			<span><img src="./images/wx2.png" alt=""></span>
		</div>
	</div>
	<div class="footer"></div>
</div>
</template>

<script>
export default {
  name: "",
};
</script>

<style scoped>
.box1{
	width: 1920px;
	height: 765px;
}
.top{
	position: relative;
	width: 1920px;
	height: 100px;
	background-color: #b86820;
	background-image: url("./images/未标题-1.png");
}
.top-1{
	position: absolute;
	margin-top: 10px;
	left: 50%;
	margin-left: -68px;
}
.top-2{
	position: absolute;
	margin-top: 25px;
	left: 70%;
}
.content{
	height: 570px;
	width: 1920px;
	background-color: #2f2f2f;
}
.footer{
	width: 1920px;
	height: 50px;
	background-color: #2a2a2a;
}
.content-1{
	position: absolute;
	width: 1920px;
	height: 170px;
	background-image: url("./images/未标题-2.png");
	margin-top: 40px;
}
.content-1>p{
	font-size: 40px;
	color: #ffffff;
	line-height: 179px;
	margin-left: 400px;
}
.content-1>span{
	position: absolute;
	margin-top: -140px;
}
</style>