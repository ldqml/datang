<template>
    <div class="box1">
        <div class="top">
		<div class="img">
			<img src="../../assets/images/未标题-1.png" alt="">
		</div>
		<div class="msg1">
			<p class="text1">行业应用</p>
	        <p class="text2">INDUSTRY SERVICE</p>
		</div>
	    </div>
        <div class="bg">
            <div class="img1">
                <img src="./images/未标题-1.png" alt="">
            </div>
            <div class="img2">
                <img src="./images/未标题-2.png" alt="">
            <div class="img3">
                <img src="./images/未标题-3.png" alt="">
            </div>
            <div class="img4 active">
                <img src="./images/未标题-4.png" alt="">
            </div>
            <div class="img5">
                <img src="./images/未标题-5.png" alt="">
            </div>
            <div class="img6">
                <img src="./images/未标题-6.png" alt="">
            </div>
            <div class="img7">
                <img src="./images/未标题-7.png" alt="">
            </div>
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
	position: relative;
}
.msg1{
	position: absolute;
	left: 50%;
	margin-left: -52px;
	margin-top: 48px;
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
.bg>.img{
        background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
}
</style>