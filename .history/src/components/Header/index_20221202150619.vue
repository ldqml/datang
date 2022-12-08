<template>
  <div class="box1">
    <p class="msg1"><b>{{msg1}}</b></p>
  </div>
</template>
<script>
export default {
  data(){
    return{
      msg1:"欢迎来到浙江宇辉电子有限公司网站!"
    }
  }
};
</script>

<style>
.box1{
	width: 1920px;
	height: 35px;
	border: 1px solid gray;
  background-color: #f1f1f1;
}
.msg1{
  font-size: 12px;
  color: #6b6b6b;
  line-height: 35px;
}
</style>
