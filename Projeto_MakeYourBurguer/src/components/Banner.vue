<template>
    <div class="main-banner">
        <h1>Make Your burguer </h1>
    </div>
</template>


<script>

export default {
    name: 'Banner',

}

</script>

<style scoped>

.main-banner {
    background-image: url('../../public/img/burger.jpeg');
    background-position: 0 -250px;
    background-size: cover;
    height: 500px;
    display: flex;
    align-items: center;
    justify-content: flex-start
}

.main-banner h1 {
    color: #FFF;
    text-align: center;
    font-size: 45px;
    background-color: #222;
    padding: 15px 30px;
  }
</style>