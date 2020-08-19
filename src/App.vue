<template>
  <div id="app">
   
  </div>
</template>

<script>


export default {
  name: 'App',
  components: {
    
  }
}
import axios from "axios"
axios.get(
 "http://123.207.32.32:8000/home/multidata"
).then(res =>{console.log(res);})

</script>
<style>

</style>
