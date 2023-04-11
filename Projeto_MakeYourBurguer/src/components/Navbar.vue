<template>
<div>
    <div id="nav">
        <router-link to="/" id="logo_url">
            <img :src="logo" :alt="alt" id="logo">
        </router-link>
        <router-link to="/">Home</router-link> 
        <router-link to="/Pedidos">Pedidos</router-link>
    </div>
</div>
</template>

<script>
export default {
    name: 'Navbar',
    props: {
        logo: {
            type: String,
            required: true
        },
        alt: {
            type: String,
            required: true
        }
    }
}

</script>

<style>
#nav {
    background-color: #222;
    border-bottom: 4px solid #111;
    padding: 10px 25px;
    display: flex;
    justify-content: flex-end;
    align-items: center;
}

#nav #logo_url {
    margin: auto;
    margin-left: 10px
}

#logo {
    height: 40px;
    width: 40px;
}

#nav a {
    color: #fcba22;
    text-decoration: none;
    transition: .5s;
    margin: 5px
}

#nav a:hover {
    color: #fff;
}

</style>