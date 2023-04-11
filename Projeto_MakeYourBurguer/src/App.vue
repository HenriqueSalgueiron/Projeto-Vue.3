<template>
  <div>
    <Navbar :logo="logo_src" :alt="app_name" />
    <div>
      <router-view></router-view>
    </div>
    <Footer />
  </div>
</template>

<script>
  import Navbar from './components/Navbar.vue'
  import Footer from './components/Footer.vue'
  export default {
    components: {
      Navbar,
      Footer
    },
    data () { return {
      logo_src: './img/logo.png',
      app_name: 'Make your burguer'
    }}
  }
</script>

<style> 

* {
    font-family: Helvetica;
    padding: 0;
    margin: 0;
    box-sizing: border-box;
  }

.mainContainer {
  margin: 50px;
  min-height: 250px;
}

h1 {
  text-align: center;
  font-size: 40px;
  margin-bottom: 50px;
  color: #222;
}

</style>
