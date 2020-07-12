<template>
  <div id="app">

    <header-links-component />
    
    <div>
      <router-view></router-view>
    </div>
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
