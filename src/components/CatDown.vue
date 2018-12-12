<template>  
  <div class="hello">
    <img src="https://jedscloud.i234.me/line_bot_photo/S__101023876.jpg" width="25%">
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
export default {
  name: 'CatDown',
  data () {
    return {
      msg: '這是連結二，所以貓咪躺著'
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