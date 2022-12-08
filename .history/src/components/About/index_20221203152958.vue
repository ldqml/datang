<template>
  <div class="box1">
    <div class="top">
      <div class="img">
        <img class="top-img" src="../../assets/images/未标题-1.png" alt="" />
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
      <div class="left"></div>
      <div class="right-img1"></div>
      <div class="right-img2"></div>
      <div class="right">
        <p style="font-size:20px">公司介绍</p>
        <p style="font-size:14px;color:#555555;line-height: 24px;">
          浙江宇辉电子有限公司创立于1997年，专注于设计制作高精密模具，加
          工各种精密五金冲压件、拉伸件及精密机加工件，在电子元件行业具有
          17年生产管理经验和成熟的合作团队。公司拥有25T-145T高速冲床30余
          台(日本京利，台湾协易，奥玛特等)，高品质模具生产线（日本WAIDA
          光学曲线研磨设备、台湾大水磨床，慢走丝加工设备等）及CNC数控车
          床，宁江全自动车床，高精度切割机械设备。产品广泛应用于继电器，
          连接器，接插件，微型马达，电子，汽车，航空等配件领域...
        </p>
        <span><img src="./images/未标题-5.png" alt=""></span>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.box1 {
  position: relative;
  width: 1920px;
  height: 765px;
  box-shadow: 0px 1px 10px #d6cdcd;
  background-color: #ffffff;
  background-image: url("./images/未标题-1.png");
}
.top-img {
  margin-top: 210px;
}
.top {
  position: relative;
  height: 225px;
  width: 1920px;
}
.msg1 {
  position: absolute;
  left: 50%;
  margin-left: -52px;
  margin-top: 58px;
}
.text1 {
  font-size: 26px;
  color: #353535;
}
.text2 {
  font-size: 12px;
  color: #c7c7c7;
  margin-top: -18px;
  margin-left: -9px;
}
.img {
  position: absolute;
  margin-top: -210px;
  left: 50%;
  margin-left: -246px;
}
.content {
  position: relative;
}
.title {
  width: 1200px;
  height: 100px;
  position: absolute;
  left: 50%;
  margin-left: -505px;
  margin-top: -40px;
  display: flex;
}
.text {
  width: 152px;
  height: 42px;
  border-radius: 17px;
  margin-left: 100px;
  border: 1px solid #dddcdc;
  text-align: center;
  line-height: 42px;
  font-size: 18px;
  color: #515151;
}
.active {
  background-color: #163882;
  margin-left: 50px;
  font-size: 18px;
  color: #ffffff;
}
.left {
  width: 630px;
  height: 450px;
  position: absolute;
  margin-top: 50px;
  margin-left: 346px;
  box-shadow: 10px 10px 2px #d6cdcd;
  background-image: url("./images/未标题-4.png");
}
.right {
  position: absolute;
  width: 524px;
  height: 450px;
  background-color: #ffffff;
  margin-top: 50px;
  margin-left: 1010px;
}
.right>p{
    margin-left: 50px;
    margin-right: 50px;
    margin-top: 40px;
}
.right>span{
    position: absolute;
    margin-left: 50px;
    margin-top: 20px;
}
.right-img1{
    position: absolute;
    width: 288px;
    height: 192px;
    background-image: url("./images/未标题-2.png");
    margin-left: 1250px;
    margin-top: 20px;
}
.right-img2{
    position: absolute;
    width: 288px;
    height: 192px;
    background-image: url("./images/未标题-3.png");
    margin-left: 1250px;
    margin-top: 20px;
}
</style>
