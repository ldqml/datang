<template>
<div class="box4">
	<div class="content">
		<div class="list active">
			<img src="./images/未标题-1.png" alt="">
			<p class="title">机加工</p>
			<p class="msg">宇辉电子加密各种精密五金冲压件拉伸件及精...</p>
		</div>
		<div class="list"></div>
		<div class="list"></div>
		<div class="list"></div>
		<div class="list"></div>
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
	background-color: aqua;
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
	border: 1px solid green;
}
.msg{
	width: 160px;
	margin-left: 53px;
}
</style>