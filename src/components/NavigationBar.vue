<script setup>
  const emits = defineEmits(['changePage'])
</script>

<template>
  <div class="Navigation">
    <a href="javascript:;" @click="$emit('changePage', 0)">Home</a>
    <a href="javascript:;" @click="$emit('changePage', 1)">Resume</a>
    <a href="javascript:;" @click="$emit('changePage', 2)">CV</a>
    <a href="javascript:;" @click="$emit('changePage', 3)">Skills</a>
    <a href="javascript:;" @click="$emit('changePage', 4)">About This Page</a>
  </div>
</template>

<style scoped>
.Navigation {
  position: fixed;
  display: flex;
  justify-content: center;
  top:0;
  left: 0;
  width:100%;
  z-index:200;
  background-color:black;
}
.Navigation a {
  text-align: center;
  font-size: 25px;
  color: white;
  margin-right: 25px;
}
</style>

