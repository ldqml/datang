<template>
  <div id="app">
    <Header></Header>
    <Home  class="footer"></Home>
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
  margin-top: 600px;
}
</style>
