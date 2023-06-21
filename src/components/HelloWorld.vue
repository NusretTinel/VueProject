<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      Hi my name is Nusret.This is my first project in vue. 
      
    </p>
    <h3>Instagram Profile</h3>
    <ul>
      <li><a href="https://www.instagram.com/nusr_et_tinel/" target="_blank" rel="noopener">nusr_et_tinel</a></li>
      
    </ul>
    <h3>Linkedin Profile</h3>
    <ul>
      <li><a href="https://www.linkedin.com/in/nusret-tinel-96403325a/" target="_blank" rel="noopener">NusretTinel
      </a></li>
      
    </ul>
    <h3>Github Repositories</h3>
    <ul>
      <li><a href="https://github.com/NusretTinel?tab=repositories" target="_blank" rel="noopener">Github Repositories NusretTinel</a></li>
      
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>


<style scoped>
h3 {
  margin: 30px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #b99b42;
}
</style>
