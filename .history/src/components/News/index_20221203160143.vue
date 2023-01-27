<template>
    <div class="box1">
        <div class="top">
      <div class="img">
        <img class="top-img" src="../../assets/images/未标题-1.png" alt="" />
      </div>
      <div class="msg1">
        <p class="text1">新闻资讯</p>
        <p class="text2">INDUSTRY SERVICE</p>
      </div>
        </div>
        <div class="left"></div>
        <div class="right">
            <div></div>
            <div></div>
            <div></div>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
.box1 {
  position: relative;
  width: 1920px;
  height: 900px;
  background-color: #ffffff;
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
.left{
    width: 440px;
    height: 590px;
    background-color: #eeeeee;
    margin-top: 10px;
    margin-left: 350px;
}
.right{
    width: 730px;
    height: 590px;
    background-color: #eeeeee;
    margin-top: 10px;
    margin-left: 830px;
    margin-top: 0px;
}
</style>