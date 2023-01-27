<template>
    <div class="box1">
        <div class="top">
		<div class="img">
			<img class="top-img" src="../../assets/images/未标题-1.png" alt="">
		</div>
		<div class="msg1">
			<p class="text1">行业应用</p>
	        <p class="text2">INDUSTRY SERVICE</p>
		</div>
	    </div>
        <div class="content">
            <div class="title">
                <div class="text active">公司介绍</div>
                <div class="text">宇辉团队</div>
                <div class="text">车间展示</div>
                <div class="text">设备展示</div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
.box1{
    position: relative;
    width: 1920px;
    height: 765px;
    box-shadow: 0px 1px 10px #d6cdcd;
    background-color: #ffffff;
    background-image: url("./images/未标题-1.png");
}
.top-img{
	margin-top: 210px;
}
.top{
	position: relative;
    height: 225px;
    width: 1920px;
}
.msg1{
	position: absolute;
	left: 50%;
	margin-left: -52px;
	margin-top: 58px;
}
.text1{
	font-size: 26px;
	color: #353535;
}
.text2{
	font-size: 12px;
	color: #c7c7c7;
	margin-top: -18px;
	margin-left: -9px;
}
.img{
	position: absolute;
	margin-top: -210px;
	left: 50%;
	margin-left: -246px;
}
.content{
    position: relative;
}
.title{
    width: 1200px;
    height: 100px;
    position: absolute;
    left: 50%;
    margin-left: -600px;
    margin-top: -40px;
    display: flex;
}
.text{
    position: absolute;
    width: 152px;
    height: 42px;
    border-radius: 17px;
    margin-left: 100px;
    border: 1px solid #dddcdc;
}
.active{
    position: absolute;
    background-color: #163882;
    margin-left: 50px;
}
</style>