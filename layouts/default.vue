<template>
  <div id="app">
    <TheHeader />

    <div class="columns">
      <TheSideBar />

      <div class="column content">
        <nuxt/>
      </div>
    </div>
  </div>
</template>

<script>
  import TheHeader from "~/components/TheHeader";
  import TheSideBar from "~/components/TheSideBar";
  export default {
    components: {
      TheHeader,
      TheSideBar
    }
  }
</script>

<style scoped>
  #app {
    min-height: 100vh;
    background: #FAFAFA;
  }
  .columns {
    min-height: 100vh;
  }
</style>