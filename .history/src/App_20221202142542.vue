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
.footer {
  float: left;
  margin-top: 100px;
}
.home {
  float: left;
  margin-top:520px;
}
</style>
