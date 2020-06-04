<template>
  <div class="demo-container">
      demo component
  </div>
</template>

<script>
export default {
  name: 'MyDemo',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.demo-container{
  background: rgb(110, 203, 247)
}
</style>
