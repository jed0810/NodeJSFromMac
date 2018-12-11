<template>  
  <div class="hello">
    <img src="https://github.com/vuejs/awesome-vue">
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
export default {
  name: 'CatDown',
  data () {
    return {
      msg: '這是連結二，所以貓咪消失'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .hello img {
    transform: perspective(600px) rotateX(80deg);
  }
</style>