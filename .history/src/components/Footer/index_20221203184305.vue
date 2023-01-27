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
		<div class="content-4">
			<a class="a1" href="">就业布局</a><br>
			<a class="a2" href="">加机工</a><br>
			<a class="ad" href="">3D打印</a><br>
			<a class="a4" href="">产品热处理</a><br>
			<a class="a5" href="">模具热处理</a><br>
			<a class="a6" href="">模具研发设计</a><br>
			<a class="a7" href="">电机</a><br>
			<a class="a8" href="">电镀</a><br>
			<a class="a9" href="">中国模具网</a>
		</div>
		<div class="content-5">
			<a class="a1" href="">解决方案</a><br>
			<a class="a2" href="">军工</a><br>
			<a class="ad" href="">电气</a><br>
			<a class="a4" href="">电力</a><br>
			<a class="a5" href="">汽车</a><br>
			<a class="a6" href="">航天</a><br>
			<a class="a7" href="">医疗</a><br>
			<a class="a8" href="">通讯</a>
		</div>
		<div class="content-6">
			<a class="a1" href="">新闻资讯</a><br>
			<a class="a2" href="">公司新闻</a><br>
			<a class="a3" href="">行业新闻</a>
		</div>
		<span class="lianjie"><img src="./images/lianjie-1.png" alt=""></span>
		<div class="wei"><img src="./images/erweima.png" alt=""></div>
	</div>
	<div class="footer">
		<p>Copyright © 浙江宇辉电子有限公司     技术支持：盛世传媒</p>
	</div>
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
	position: relative;
	height: 640px;
	width: 1920px;
	background-color: #2f2f2f;
}
.footer{
	width: 1920px;
	height: 40px;
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
	margin-top: -130px;
	margin-left: 1200px;
}
.content-4{
	margin-top: 280px;
	position: absolute;
}
.content-4>.a1{
	font-size: 20px;
	color: #ffffff;
	margin-left: 900px;
}
.content-4>.b2,.b3,.b4,.b5,.b6,.b7,.b8,.b9{
	font-size: 14px;
	color: #888888;
	margin-left: 900px;
	line-height: 34px;
}
.content-5{
	margin-top: 280px;
	position: absolute;
}
.content-5>.a1{
	font-size: 20px;
	color: #ffffff;
	margin-left: 1050px;
}
.content-5>.a2,.ad,.a4,.a5,.a6,.a7,.a8{
	font-size: 14px;
	color: #888888;
	margin-left: 1050px;
	line-height: 34px;
}
.content-6{
	margin-top: 280px;
	position: absolute;
}
.content-6>.a1{
	font-size: 20px;
	color: #ffffff;
	margin-left: 1220px;
}
.content-6>.a2,.a3{
	font-size: 14px;
	color: #888888;
	margin-left: 1220px;
	line-height: 34px;
}
.footer>p{
	float:right;
	font-size: 14px;
	color: #888888;
	line-height: 40px;
	margin-right: 250px;
}
.lianjie{
	position: absolute;
	margin-top: 550px;
	right: 345px;
}
.wei{
	position: absolute;
	margin-top: -20px;
	left: 520px;
}
</style>