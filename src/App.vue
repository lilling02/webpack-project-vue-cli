<template>
    <h1 class="title">hello App</h1>
    <Home></Home>
</template>

<script>
import Home from './views/Home/index.vue'
export default {
    name:'App',
    components:{
        Home
    }
}
</script>

<style>
.title {
    width: 200px;
    height: 200px;
    background-color: pink;
}
</style>