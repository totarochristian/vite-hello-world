<template>
  <AppHero></AppHero>
  <AppTitle></AppTitle>
</template>

<script>
  import AppTitle from "./components/AppTitle.vue";
  import AppHero from "./components/AppHero.vue";

  export default{
    name: 'App',
    components:{
      AppTitle,
      AppHero
    },
    data(){
      return {
        
      }
    },
    methods: {
      
    },
    mounted(){
      
    }
  }
</script>

<style lang="scss" scoped>

</style>
