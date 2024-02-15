<script setup>

</script>

<template>
  <div class="main">
    <h1>Samuli Käppi</h1>
    <h2>Developer</h2>
    <div class="about">
      <h3>About Me</h3>
      <p>Hello, I'm Samuli Käppi. I'm a software developer studying at Tampere University. <br>
      I am well acquainted with a lot of concepts related to programming and <br>
      have not found a problem that I haven't been able to solve so far, and I do not plan on for that to change.
      </p>
    </div>
    <div>
      <img class="avatar" src="../avatar/avatar.jpg">
      <a href="https://www.linkedin.com/in/samuli-kappi/" target="_blank"><img class="icon" src="../avatar/Linkedin.webp" alt="linkedin"></a>
      <a href="https://github.com/SamuliKappi?tab=repositories" target="_blank"><img class="icon" src="../avatar/github-mark.svg" alt="github"></a>
    </div>
    <div>
      <ul class="info">
        <li>
          <span class="title">Age: </span>
          <span class="value">24</span>
        </li>
        <li>
          <span class="title">Residence: </span>
          <span class="value">Finland</span>
        </li>
        <li>
          <span class="title">E-mail: </span>
          <span class="value">Samuli99.kappi@gmail.com</span>
        </li>
        <li>
          <span class="title">Phone: </span>
          <span class="value">+358 503201433</span>
        </li>
      </ul>
    </div>
    
  </div>
  
</template>

<style scoped>
  .icon {
    height: 32px;
    width: 32px;
  }
  a:hover {
    background: none;
  }
 .info {
  display: inline-block;
  list-style: none;
 }
 .title {
  width: 100px;
  display: inline-block;
 }
 .avatar {
	line-height: 0;		
	display: inline-block;
	margin: 5px;
  border: 4px solid rgba(200,200,200,0.4);
	border-radius: 50%;
	transition: linear 0.25s;
  height: 128px;
  width: 128px;
}
</style>