<template>
  <div class="box1">
    <p class="msg1"><b>{{msg1}}</b></p>
    <span><img class="img1" src="./images/未标题-1.png" alt=""></span>
    <p class="msg2"><b>语言</b>:{{msg2}}</p>
  </div>
</template>
<script>
export default {
  data(){
    return{
      msg1:"欢迎来到浙江宇辉电子有限公司网站!",
      msg2:"English | 中文"
    }
  }
};
</script>

<style>
.box1{
	width: 1920px;
	height: 35px;
  background-color: #f1f1f1;
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
  margin-left: 1400px;
}
.img1{
  margin-top: -80px;
  margin-left: 1375px;
}
</style>
