<template>
  <div class="eggu">
    <h1>{{ msg }}</h1>
    <p>
      Welcome to the best E G G D O G praising site you've ever seen. 
      <br>
      <br>
      <a href="https://www.youtube.com/watch?v=P6COHwVNmik" target="_blank" rel="noopener">very important</a>
      <br>
      <br>
      <button >Don't look back, bro</button>
    
    </p>

  </div>
</template>

<script>
export default {
  name: 'egg',
  props: {
    msg: String
  }
}



</script>

<style scoped>
h3 {
  margin: 40px 0 0;
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
  color: #42b983;
}
</style>
