<template>
  <div id="app">
      {{contador}}
  </div>
</template>
<script>
  export default {

    
    data:function (){
      return{
        contador:1,
      }
    }
  }
</script>

<style>
  #app{
    background-color: currentColor;
    color: #fff;
  }
</style>