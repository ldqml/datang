<template>
  <div id="app">
    <Header></Header>
    <header-two></header-two>
    <Banner></Banner>
    <Home></Home>
    <Use class="use"></Use>
    <Footer></Footer>
  </div>
</template>

<script>
import Header from './components/Header'
import Footer from './components/Footer'
import Home from './components/Home'
import HeaderTwo from './components/HeaderTwo'
import Banner from './components/Banner'
import Use from './components/Use'
export default {
  name: 'App',
  components: {
    Header,
    Footer,
    Home,
    HeaderTwo,
    Banner,
    Use
  }
}
</script>

<style>
html, body {
  margin: 0;
  padding: 0;
}
#app{
position: absolute;
left: 50%;
margin-left:-960px ;
}
.use{
  float: left;
}
</style>
