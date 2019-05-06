<template>
  <div id="app">
    
    <logo></logo>
    
    <card></card>
    <p>MADE WITH <img src="./assets/logo.png" alt="" style="width:3vh; transform:translateY(1vh)"> BY <a href="http://www.theogeiller.com">THEO GEILLER</a></p>
  
  </div>

</template>



<script>
 
import card from "./components/card.vue"
import logo from "./components/logo.vue"

export default {

  components: {

    card,
    logo

  },
  

}


</script>


<style lang="scss">

@import '@/scss/base.scss';

a{text-decoration: none;
  color: rgb(129, 129, 129);}
  a:hover{text-decoration: none;
  color: rgb(26, 150, 74);}


</style>
