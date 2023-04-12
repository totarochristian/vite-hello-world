<template>
  <div id="heroDiv">
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

<style lang="css" scoped>
  #heroDiv{
    width: 100%;
    height: 100%;
    position: relative;
  }
  #heroDiv>img{
    width: 100%;
    height: 100%;
    object-fit: cover;
    filter: brightness(80%);
  }
</style>