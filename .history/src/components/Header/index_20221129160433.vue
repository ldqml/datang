<template>
  <div class="navbar-wrapper">
    <div id="myCarousel" class="carousel slide carousel-fade w-100" data-ride="carousel">
      <!-- Indicators -->
      <ol class="carousel-indicators">
        <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
        <li data-target="#myCarousel" data-slide-to="1"></li>
      </ol>
      <div class="carousel-inner" role="listbox">
        <div class="item active">
          <img
            class="first-slide"
            src="./images/banner.png"
            alt="First slide"
          />
          <div class="container">
            <div class="carousel-caption">
              <h1>专注于技术服务驻场远程服务商</h1>
              <h2>给企业提供灵活用工技术研发人才</h2>
              <h3>解决企业招聘难题</h3>
            </div>
          </div>
        </div>
        <div class="item">
          <img
            class="second-slide"
            src="./images/banner.png"
            alt="Second slide"
          />
          <div class="container">
            <div class="carousel-caption">
              <h1>Another example headline.</h1>
              <p>
              </p>
              <p>
                <a class="btn btn-lg btn-primary" href="#" role="button"
                  >Learn more</a
                >
              </p>
            </div>
          </div>
        </div>
      </div>
      <a
        class="left carousel-control"
        href="#myCarousel"
        role="button"
        data-slide="prev"
      >
        <span
          class="glyphicon glyphicon-chevron-left"
          aria-hidden="true"
        ></span>
        <span class="sr-only">Previous</span>
      </a>
      <a
        class="right carousel-control"
        href="#myCarousel"
        role="button"
        data-slide="next"
      >
        <span
          class="glyphicon glyphicon-chevron-right"
          aria-hidden="true"
        ></span>
        <span class="sr-only">Next</span>
      </a>
    </div>
    <div class="container">
      <nav class="navbar">
        <div class="container-fluid">
          <!-- Brand and toggle get grouped for better mobile display -->
          <div class="navbar-header">
            <a class="navbar-brand" href="#">
              <img alt="Brand" src="./images/logo.png" />
            </a>
          </div>
          <p class="navbar-text">首页</p>
          <p class="navbar-text">驻场服务</p>
          <p class="navbar-text">远程服务</p>
          <form class="navbar-form navbar-left" role="search">
            <div class="form-group">
              <input type="text" class="form-control" placeholder="输入想输入的内容" />
            </div>
          </form>
          <p class="navbar-text">股份投资</p>
          <p class="navbar-text">人才投资</p>
          <p class="navbar-text text-ts">招聘app</p>
          <p class="navbar-text">登入</p>
          <p class="navbar-text">注册</p>
        </div>
        <!-- /.container-fluid -->
      </nav>
    </div>
    <div class="footerContent">
        <h3>前端无忧教育 隶属于驻场教育旗下平台</h3>
    </div>
    <footer class="bg-dark p-4 text-light text-center">
			<div class="container">
				<h3>合作伙伴</h3>
				<ul class="fa-ul">
					<li class="list-inline-item"><a href="#"><i class="fa-cc-discover fa-2x text-white" aria-hidden="true"></i></a></li>
					<li class="list-inline-item"><a href="#"><i class="fa-cc-discover fa-2x text-white" aria-hidden="true"></i></a></li>
					<li class="list-inline-item"><a href="#"><i class="fa-cc-discover fa-2x text-white" aria-hidden="true"></i></a></li>
					<li class="list-inline-item"><a href="#"><i class="fa-cc-discover fa-2x text-white" aria-hidden="true"></i></a></li>
					<li class="list-inline-item"><a href="#"><i class="fa-cc-discover fa-2x text-white" aria-hidden="true"></i></a></li>
					<li class="list-inline-item"><a href="#"><i class="fa-cc-discover fa-2x text-white" aria-hidden="true"></i></a></li>
					<li class="list-inline-item"><a href="#"><i class="fa-cc-discover fa-2x text-white" aria-hidden="true"></i></a></li>
					<li class="list-inline-item"><a href="#"><i class="fa-cc-discover fa-2x text-white" aria-hidden="true"></i></a></li>
				</ul>
				<p class="m-1">企业培训 | 合作事宜 | 版权投诉</p>
				<p>赣ICP备12345678.© 2019-2025 chaoliuchuanda.Powered by chaopai.</p>
			</div>
		</footer>
  </div>
  
</template>
<script>
export default {};
</script>

<style>
.navbar-text{
font-size: 14px;
font-family: Microsoft YaHei;
color: #FFffFF;
line-height: 60px;
}
.form-control{
  border-radius: 19px;
  width: 248px;
  height: 38px;
  margin-top: 18px;
  margin-right: 20px;
  margin-left: 20px;
}
.carousel{
  position:absolute;
  top: 0px;
}
.text-ts{
  margin-left: 60px;
}
</style>
