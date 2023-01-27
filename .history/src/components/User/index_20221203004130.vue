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
        <div class="bg">
            <div class="img1">
            </div>
            <div class="img2">
            </div>
            <div class="img3">
            </div>
            <div class="img4 active">
            </div>
            <div class="img5">
            </div>
            <div class="img6">
            </div>
            <div class="img7">
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
.top-img{
	margin-top: 204px;
}
.title{
	font-size: 18px;
	color: #353535;
}
.top{
	position: relative;
    height: 302px;
    width: 1920px;
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
.bg{
    display: flex;
    position: absolute;
    left: 0;
    margin-left: -1375px;
}
.img1{
    width: 220px;
    height: 540px;
    background-image: url("./images/未标题-1.png");
}
.img2{
    position: absolute;
    width: 220px;
    height: 540px;
    background-image: url("./images/未标题-2.png");
    margin-left: 0px;
    margin-top:0px;
}
.img3{
    width: 220px;
    height: 540px;
    background-image: url("./images/未标题-3.png");
}
.img4{
    width: 602px;
    height: 540px;
    background-image: url("./images/未标题-4.png");
}
.img5{
    width: 220px;
    height: 540px;
    background-image: url("./images/未标题-5.png");
}
.img6{
    width: 220px;
    height: 540px;
    background-image: url("./images/未标题-6.png");
}
.img7{
    width: 220px;
    height: 540px;
    background-image: url("./images/未标题-7.png");
}
</style>