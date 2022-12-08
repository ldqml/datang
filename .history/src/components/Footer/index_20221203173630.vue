<template>
<div class="box1">
	<div class="top">
		<span class="top-1"><img src="./images/未标题-3.png" alt=""></span>
		<span class="top-2"><img src="./images/wx1.png" alt=""></span>
	</div>
	<div class="content"></div>
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
	height: 145px;
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
	margin-top: 45px;
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
</style>