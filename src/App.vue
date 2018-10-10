<template>
  <div id="app">
    <Navbar></Navbar>
    <Header></Header>
    <Content title="Hello World"></Content>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Header from './components/Header.vue'
import Navbar from './components/Navbar.vue'
import Content from './components/Content.vue'

export default {
  name: 'app',
  components: {
    HelloWorld,
    Header,
    Navbar,
    Content
  }
}
</script>

<style>
</style>