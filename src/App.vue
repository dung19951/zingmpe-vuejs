<template>
  <div id="app">
    <SideBar/>
    <Header/>
    <Footer/>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import SideBar from './components/SideBar.vue'
import Footer from "@/components/Footer";

export default {
  name: 'App',
  components: {
    Footer,
    Header,
    SideBar
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
</style>
