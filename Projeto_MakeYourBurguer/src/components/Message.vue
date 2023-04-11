<template>
<div class="message-container">
    <p>{{ msg }}</p>
</div>
</template>

<script>
export default {
    name: 'Message',
    props: {
        msg: {
            type: String,
            required: true
        }
    }

}
</script>

<style scoped>

.message-container {
    color: #004085;
    background-color:  #CCE5FF;
    border: 2px solid #b8daff;
    border-radius: 5px;
    padding: 10px;
    width: fit-content;
    margin: 30px auto;

}
</style>