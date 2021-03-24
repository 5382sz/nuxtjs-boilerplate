<template> 
  <div class="container">
    <div class="home__title"> {{ title }}</div>
  </div>
</template>

<script>
export default {
  data () {
    return {
      title: 'my nuxtjs boilerplate',
    }
  }
}
</script>

<style>
.home__title {
  min-height: 25vh;
  display: flex;
  justify-content: center;
  align-items: center;
  margin: auto; 
  text-align: center;
  color: white;
}
</style>