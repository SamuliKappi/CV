<script setup>
  const yep = true
</script>

<template>
  <h1 class="main-title">Resume</h1>
  <div class="row">
    <div class="block">
      <h2 class="timeline-title">Education</h2>
      <div class="timeline">
        <div class="timeline-item">
          <h4 class="title">Upper secondary education</h4>
          <span class="duration">2015-2018</span>
          <span class="title-small">Sammon Keskuslukio</span>
        </div>
        <div class="timeline-item">
          <h4 class="title">Bachelors and Masters degree</h4>
          <span class="duration">2019-Present</span>
          <span class="title-small">Tampere University</span>
        </div>
      </div>
    </div>
    <div class="block">
      <h2 class="timeline-title">Experience</h2>
      <div class="timeline">
        <div class="timeline-item">
          <h4 class="title">Programmer</h4>
          <span class="duration">Aug 2018 - Mar 2019</span>
          <span class="title-small">Finnish Defence Forces</span>
          <p class="description">Worked as a developer and a technical support for VBS3-simulator</p>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.main-title {
  text-align: center;
}
.row {
    margin-bottom: 30px;
    display: grid;
    grid-template-columns: 1fr 1fr;
}
.block {
  margin: 40px;
}
.timeline-item {
    position: relative;
    padding: 15px 20px 10px;
    margin-left: 20px;
    margin-bottom: 20px;
    border-left: 2px solid #2eca7f;
    box-shadow: 0 0 3px 0 rgba(0,0,0,.2);
    width: 400px;
}
.timeline {
    border-left: 2px solid #e0e0e0;
    padding: 15px 0;
}
.title {
    display: block;
    margin: 0;
    font-size: 16px;
    line-height: 1.2em;
}
.duration {
    display: inline-block;
    font-size: 12px;
    line-height: 1.2em;
    color: #2eca7f;
    margin-bottom: 8px;
}
.title-small {
    display: inline-block;
    font-size: 12px;
    line-height: 1.2em;
    color: #9e9e9e;
    margin-left: 5px;
    margin-bottom: 8px;
    padding-left: 8px;
    border-left: 1px solid #e0e0e0;
}
</style>