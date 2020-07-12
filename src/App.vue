<template>
  <div id="app">
    
    <header-links-component />
    
    <router-view></router-view>

  </div>
</template>

<script>
  import HeaderLinksComponent from "@/components/base/HeaderLinksComponent";
  export default {
    components: { HeaderLinksComponent}
  }
</script>

<style>

</style>
