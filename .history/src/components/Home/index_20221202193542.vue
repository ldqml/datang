<template>
<div class="box4">
	<div class="content">
		<div class="list active"></div>
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
}
.list{
	width: 266px;
	height: 600px;
}
</style>