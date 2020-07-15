<template>
  <div id="app">

    <header-links-component />
    
    
    <div>
      <router-view></router-view>
    </div>

    <footer-component />
  </div>
</template>

<script>
  import HeaderLinksComponent from "@/components/base/HeaderLinksComponent";
  import FooterComponent from "@/components/base/FooterComponent";
  export default {
    components: { HeaderLinksComponent, FooterComponent}
  }
</script>

<style>

</style>
