<script>
  import Jumbo from './components/Jumbo.vue'
  export default{
    name: 'App',
    components:{
      Jumbo
    },
    data(){
      return{
        titolo: 'Ciao Vue'
      }
    }
  }
</script>

<template>
  <Jumbo />
  <h1>{{titolo}}</h1>
</template>

<style>
</style>