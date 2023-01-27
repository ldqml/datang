<template>
    <div class="box2">
        <span class="img1"><img src="./images/未标题-1.png" alt=""></span>
        <div class="box3">
            <a class="nav active" href="">{{msg1}}</a>
            <a class="nav" href="">{{msg2}}</a>
            <a class="nav" href="">{{msg3}}</a>
            <a class="nav" href="">{{msg4}}</a>
            <a class="nav" href="">{{msg5}}</a>
            <a class="nav" href="">{{msg6}}</a>
            <a class="nav" href="">{{msg7}}</a>
            <a class="nav" href="">{{msg8}}</a>
            <a class="nav" href="">{{msg9}}</a>
            <a class="nav" href="">首页</a>
        </div>
    </div>
</template>

<script>
export default {
    data(){
        return{
            msg1:"首页",
            msg2:"关于宇辉",
            msg3:"产业布局",
            msg4:"产品中心",
            msg5:"宇辉服务",
            msg6:"解决方案",
            msg7:"案例中心",
            msg8:"新闻资讯",
            msg9:"联系我们",
            msg10:""
        }
    }
}
</script>

<style scoped>
.box2 {
    width: 1920px;
    height: 100px;
    background-color: #f1f1f1;
}
.img1{
    margin-left: 223px;
    line-height: 100px;
}
.box3{
    display: flex;
    justify-content: center;
    align-items: center;
    width: 998px;
    height: 80px;
    background-color:yellow;
    margin-left: 680px;
    margin-top: -90px;
}
.nav{
    margin-left: 45px;
}
</style>