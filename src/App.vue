<template>
  <div id="app">
    {{contador}}
    <button @click="contador += 1">Adicionar</button>
  </div>
</template>
<script>
  export default {
    data(){
      return{
        contador:1,
      }
    }
  }
</script>

<style>
  #app{
  }
</style>