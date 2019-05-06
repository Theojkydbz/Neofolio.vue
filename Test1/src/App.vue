<template>
  <div id="app">

    <img src="./assets/logo.png" alt="">

    <h1>{{ msg }}</h1>

    <counter></counter>

    <alert></alert>

  </div>

</template>



<script>

import alert from './alert.vue'
import counter from './counter.vue'

export default {

  components: { alert },

  data () {

    return {

      msg: "Hello_World"

    }

  }

}


</script>


<style lang="scss">

@import '@/scss/base.scss';

</style>
