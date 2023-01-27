<template>
    <div class="swiper-container">
            <span class="img2"><img src="./images/未标题-2.png" alt=""></span>
            <div class="swiper-wrapper">
              <div class="swiper-slide"><img src="./images/未标题-1.png" alt=""></div>
              <div class="swiper-slide"><img src="./images/未标题-1.png" alt=""></div>
            </div>
                <div class="swiper-button-prev swiper-button-white"></div>
                <div class="swiper-button-next swiper-button-white"></div>
                <span class="img2"><img src="./images/未标题-2.png" alt=""></span>
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
    loop: true,
    autoplay: {
            delay: 5000,
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
    position: relative;
    width: 1920px;
    height: 730px;
}
.swiper-button-prev{
    margin-left: 288px;
}
.swiper-button-next{
    margin-right: 288px;
}
.img2{
  position: absolute;
  margin-left: 850px;
  margin-top: 300px;
  z-index: 999;
}
</style>



