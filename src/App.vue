<script setup>
//import HelloWorld from './components/HelloWorld.vue'
import sumapts from './components/sumapts.vue';
import mostrar from './components/mostrar.vue';

</script>

<template>

  <nav class="navbar">
    <ul><a href="../index.html">Inicio</a></ul>
    <ul><a href="../Blog.html">Blog</a></ul>
  </nav>


  <mostrar msg='mostrar' />
  <sumapts msg="sumar" />
  <!-- <HelloWorld msg="Hello" /> -->

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
ul{
  background-color: rgb(86, 44, 251);
  color: aqua;
  display: flex;
  width: 25%;
  align-items: center;
}
a{
  color:antiquewhite;
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 1rem;
}
</style>
