<script setup>

</script>

<template>
  <h2 class="mainTitle">Skills</h2>
  <div class="mainBox">
    <div class="box">
      <h3>Languages</h3>
      <ul>
        <li>Python</li>
        <li>JavaScript</li>
        <li>Vue</li>
        <li>React</li>
        <li>C++</li>
        <li>C</li>
      </ul>
    </div>
    <div class="box">
      <h3>Technologies</h3>
      <ul>
        <li>Docker</li>
        <li>Git</li>
      </ul>
    </div>
    <div class="box">
      <h3>Databases</h3>
      <ul>
        <li>SQL</li>
        <li>Neo4J</li>
        <li>MongoDB</li>
      </ul>
    </div>
  </div>
</template>

<style>
  .mainBox {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
  }
  .box {
    margin: 40px;
  }
  .mainTitle {
    text-align: center;
  }

</style>