<template>
  <div id="app">
    <sample-component />
    <child-component />
  </div>
</template>

<script>
import SampleComponent from "./components/SampleComponent.vue"
import ChildComponent from "./components/ChildComponent.vue"

export default {
  name: 'App',
  components: {
    SampleComponent,
    ChildComponent
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
