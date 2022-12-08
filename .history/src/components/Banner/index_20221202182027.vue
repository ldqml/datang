<template>
    <div class="swiper-container" ref="mySwiper">
            <div class="swiper-wrapper">
              <div class="swiper-slide"><img src="./images/未标题-1.png" alt=""></div>
              <div class="swiper-slide"><img src="./images/未标题-1.png" alt=""></div>
            </div>
            <!-- 如果需要分页器 -->
            <div class="swiper-pagination"></div>

            <!-- 如果需要导航按钮 -->
            <div class="swiper-button-prev swiper-button-white"></div>
            <div class="swiper-button-next swiper-button-white"></div>
          </div>
</template>

<script>
import Swiper from 'swiper';  
export default {
    data(){
        return{

        }
    },
    mounted(){
        var mySwiper = new Swiper ('.swiper-container', {
    loop: true, // 循环模式选项
    autoplay: {
            delay: 5000,
            },
    pagination: {
      el: '.swiper-pagination',
    },
    
    navigation: {
      nextEl: '.swiper-button-next',
      prevEl: '.swiper-button-prev',
    },
  })
    }
}
</script>

<style>
.swiper-container{
    width: 1920px;
    height: 730px;
}
.swiper-button-prev{
    margin-left: 288px;
    border: 1px solid white;
}
.swiper-button-next{
    margin-right: 288px;
    border: 1px solid white;
    border-left-width: 70px;
}
</style>



