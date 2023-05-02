<script>
  import AppTitle from "./components/AppTitle.vue"

  export default{
      name: 'App',
      components:{
        AppTitle
      }
    }
</script>

<template>
  <div id="container0" class="vh-100 d-flex justify-content-center align-items-center">
    <AppTitle/>  
  </div>
</template>

<style scoped>
  #container0{
    background-color: beige;
  }
</style>

