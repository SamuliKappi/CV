<script setup>
  import { ref } from 'vue'
  import NavigationBar from "./components/NavigationBar.vue"
  import Welcome from './components/Welcome.vue'
  import Resume from './components/Resume.vue'
  import About from './components/About.vue'
  import Cv from './components/Cv.vue'
  const currentPage = ref(0)
  function changePage(p) {
    currentPage.value = p
  }
</script>


<template>
  <NavigationBar @changePage="changePage"></NavigationBar>
  <div class="main">
    <Welcome v-if="currentPage === 0"></Welcome>
    <Resume v-else-if="currentPage === 1"></Resume>
    <Cv v-else-if="currentPage === 2"></Cv>
    <About v-else-if="currentPage === 3"></About>
  </div>
</template>

<style>
  .main {
    margin-top: 25px;
  }
  #app {
    display: flex;
    justify-content: center;
  }
</style>