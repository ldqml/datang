<template>
  <div id="app">
    <Header></Header>
    
    <Home></Home>
    <Footer></Footer>
  </div>
</template>

<script>
import Header from './components/Header'
import Footer from './components/Footer'
import Home from './components/Home'
import HeaderTwo from './components/HeaderTwo'
export default {
  name: 'App',
  components: {
    Header,
    Footer,
    Home,
    HeaderTwo
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
</style>
