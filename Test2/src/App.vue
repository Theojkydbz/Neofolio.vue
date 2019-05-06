<template>
  <div id="app">

    <img src="./assets/logo.png" alt="">

    <todo></todo>


  </div>

</template>



<script>

import todo from "./components/todo.vue"

export default {

  components: {

    todo

  }

}


</script>


<style lang="scss">

@import '@/scss/base.scss';

</style>
