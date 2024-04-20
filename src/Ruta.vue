<script setup>
import HelloWorld from './components/HelloWorld.vue'
//import Products from './components/Products.vue'
//import mostrar from './components/mostrar.vue';
</script>

<template>

    <nav class="navbar">
        <ul><a href="../index.html">Inicio</a></ul>
        <ul><a href="../Blog.html">Blog</a></ul>
       
    </nav>
    <h1>Corinto</h1>
    <!--  <Products msg="Productos" /> -->
    <!-- <mostrar msg='mostrar' /> -->
    <HelloWorld msg="Hello" />

</template>

<style scoped>
.logo {
    height: 6em;
    padding: 1.5em;
    will-change: filter;
    transition: filter 300ms;
}

.logo:hover {
    filter: drop-shadow(0 0 2em #646cffaa);
}

.logo.vue:hover {
    filter: drop-shadow(0 0 2em #42b883aa);
}
</style>