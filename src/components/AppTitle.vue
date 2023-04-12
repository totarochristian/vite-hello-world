<template>
  <div id="titleDiv">
    <h1>{{ title }}</h1>
  </div>
</template>

<script>
  export default {
    name: "AppTitle",
    data(){
      return{
        title: "La mia prima app con Vite!"
      }
    },
    methods: {

    }
  }
</script>

<style lang="css" scoped>
  #titleDiv{
    width: 100%;
    height: 100%;
    position: absolute;
    color: white;
  }
  #titleDiv>h1{
    font-size: 4rem;
    text-align: center;
    margin: 0;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%,-50%);
    z-index: 1000;
  }
  @media screen and (max-width: 450px){
    #titleDiv>h1{
      font-size: 2rem!important;
    }
  }
  @media screen and (max-width: 700px){
    #titleDiv>h1{
      font-size: 3rem;
    }
  }
</style>