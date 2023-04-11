<template>
  <div>
    <Banner />
    <div class="main-container">
      <h1>Monte o seu burger:</h1>
      <Form />
    </div>
  </div>
</template>

<script>
import Banner from '../components/Banner.vue'
import Form from '../components/BurguerForm.vue'
export default {
  name: 'Home',
  components: {
    Banner,
    Form
  }
}
</script>