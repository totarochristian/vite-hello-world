<template>
  <div id="hero">
    <AppTitle></AppTitle>
    <img src="../assets/images/Super-hero-head-sm.jpg" alt="Hero">
  </div>
</template>

<script>
  import AppTitle from "./AppTitle.vue";

  export default {
    name: "AppHero",
    components:{
      AppTitle
    },
    data(){
      return{
        
      }
    },
    methods: {

    }
  }
</script>

<style lang="scss" scoped>

</style>