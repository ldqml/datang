<template>
  <div id="app">
    <Header></Header>
    <header-two></header-two>
    <Banner></Banner>
    <Home></Home>
    <User></User>
    <About></About>
    <News></News>
    <Footer></Footer>
  </div>
</template>

<script>
import Header from './components/Header'
import Footer from './components/Footer'
import Home from './components/Home'
import HeaderTwo from './components/HeaderTwo'
import Banner from './components/Banner'
import User from './components/User'
import About from './components/About'
import News from './components/News'
export default {
  name: 'App',
  components: {
    Header,
    Footer,
    Home,
    HeaderTwo,
    Banner,
    User,
    About,
    News,
  }
}
</script>

<style>
html, body {
  margin: 0;
  padding: 0;
  overflow: hidden;
}
#app{
position: absolute;
left: 50%;
margin-left:-960px ;
}
</style>
