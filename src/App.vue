<template>
<div id="app">
  <NavBar/>
  <Content/>

</div>
</template>

<script>
import NavBar from './components/NavBar.vue'
import Content from './components/Content.vue'

export default {
  name: 'App',
  components: {
    NavBar,
    Content
  }
}
</script>

<style>

</style>
