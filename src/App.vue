<template>
  <div id="app">
<!--    <ExcelEditPreview />-->
    <HelloWorld></HelloWorld>
  </div>

</template>

<script>
import ExcelEditPreview from "@/components/ExcelEditPreview.vue";
import HelloWorld from "@/components/HelloWorld.vue";
export default {
  name: 'App',
  components: {
    // eslint-disable-next-line
    ExcelEditPreview,
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
