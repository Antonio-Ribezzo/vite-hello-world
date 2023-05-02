<script>
  import AppTitle from "./components/AppTitle.vue"
  import AppHero from "./components/AppHero.vue"
  export default{
      name: 'App',
      components:{
        AppTitle,
        AppHero
      }
    }
</script>

<template>
  <div id="container0" class="vh-100 d-flex flex-column justify-content-center align-items-center">
    <AppTitle/>  
    <AppHero/>
  </div>
</template>

<style scoped>
  #container0{
    background-color: #3f3f3c;
  }
</style>

