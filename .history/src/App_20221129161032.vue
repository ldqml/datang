<template>
  <div id="app">
    <Header></Header>
    <Footer class="footer"></Footer>
  </div>
</template>

<script>
import Header from './components/Header'
import Footer from './components/Footer'
export default {
  name: 'App',
  components: {
    Header,
    Footer
  }
}
</script>

<style>
.footer {
  float: left;
  margin-bottom:1opx;
}
</style>
