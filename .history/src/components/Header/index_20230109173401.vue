<template>
  <div class="box1">
    <p class="msg1"><b>{{msg1}}</b></p>
    <span><img class="img1" src="./images/未标题-1.png" alt=""></span>
    <p class="msg2"><b>语言</b> :{{msg2}}</p>
    <span><img class="img2" src="./images/phone-1.png" alt=""></span>
    <p class="msg3"><b>服务热线</b> :{{msg3}}</p>
  </div>
</template>
<script>
export default {
  data(){
    return{
      msg1:"欢迎来到浙江宇辉电子有限公司网站!",
      msg2:"English | 中文",
      msg3:"0577-62311227"
    }
  }
};
</script>

<style scope>
.box1{
	width: 1920px;
	height: 35px;
  background-color: #f1f1f1;
  border-bottom: 1px solid #d5d5d5;
}
.msg1{
  font-size: 12.2px;
  color: #6b6b6b;
  line-height: 35px;
  margin-left: 223px;
}
.msg2{
  color: #585858;
  font-size: 12px;
  margin-left: 1402px;
  margin-top: -55px;
}
.msg3{
  color: #585858;
  font-size: 12px;
  margin-left: 1535px;
  margin-top: -55px;
}
.img1{
  margin-top: -78px;
  margin-left: 1375px;
}
.img2{
  margin-top: -60px;
  margin-left: 1510px;
}
</style>
