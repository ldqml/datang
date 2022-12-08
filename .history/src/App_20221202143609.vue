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
export default {
  name: 'App',
  components: {
    Header,
    Footer,
    Home
  }
}
</script>

<style>
#app{
position: absolute;
left: 50%;
margin-left: ;
}
</style>
