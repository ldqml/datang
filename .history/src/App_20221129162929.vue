<template>
  <div id="app">
    <Header></Header>
    <Footer class="footer"></Footer>
    <Home></Home>
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
  margin-top: 1000px;
}
</style>
