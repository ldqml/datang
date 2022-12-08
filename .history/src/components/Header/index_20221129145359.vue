<template>
  <div class="navbar-wrapper">
      <div class="container">

        <nav class="navbar navbar-default">
  <div class="container-fluid">
    <!-- Brand and toggle get grouped for better mobile display -->
    <div class="navbar-header">
      <a class="navbar-brand" href="#">
        <img alt="Brand" src="./images/logo.png">
      </a>
    </div>

    <!-- Collect the nav links, forms, and other content for toggling -->
  </div><!-- /.container-fluid -->
</nav>

      </div>
      <div id="myCarousel" class="carousel slide" data-ride="carousel">
      <!-- Indicators -->
      <ol class="carousel-indicators">
        <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
        <li data-target="#myCarousel" data-slide-to="1"></li>
      </ol>
      <div class="carousel-inner" role="listbox">
        <div class="item active">
          <img class="first-slide" src="./images/banner.png" alt="First slide">
          <div class="container">
            <div class="carousel-caption">
              <h1>专注于技术服务型人才</h1>
              <h2>给企业提供灵活用工技术研发人才</h2>
              <h3>解决企业招聘难题</h3>
            </div>
          </div>
        </div>
        <div class="item">
          <img class="second-slide" src="./images/banner.png" alt="Second slide">
          <div class="container">
            <div class="carousel-caption">
              <h1>Another example headline.</h1>
              <p>Cras justo odio, dapibus ac facilisis in, egestas eget quam. Donec id elit non mi porta gravida at eget metus. Nullam id dolor id nibh ultricies vehicula ut id elit.</p>
              <p><a class="btn btn-lg btn-primary" href="#" role="button">Learn more</a></p>
            </div>
          </div>
        </div>
      </div>
      <a class="left carousel-control" href="#myCarousel" role="button" data-slide="prev">
        <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
        <span class="sr-only">Previous</span>
      </a>
      <a class="right carousel-control" href="#myCarousel" role="button" data-slide="next">
        <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
        <span class="sr-only">Next</span>
      </a>
    </div>
    </div>
    
</template>

<script>
export default {
    
}
</script>

<style>

</style>
