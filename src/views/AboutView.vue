<template lang="">
  <div>
    <About></About>
    <router-view></router-view>
  </div>
</template>
<script>
import About from '../components/About.vue'
export default {
  components : {
    About
  }
}
</script>
<style lang="">
  
</style>
