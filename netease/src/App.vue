<template>
  <div id="app">
    <router-view></router-view>
    <FooterGuide></FooterGuide>
  </div>
</template>

<script>
  import FooterGuide from  './components/FooterGuide/FooterGuide'
export default {
  components:{
    FooterGuide
  }
}
</script>

<style>

</style>
