<template>
  <div class="bg-light" id="app">
    <router-view></router-view>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'
import PostsExample from './components/Posts'
import Contact from './components/Contact'
import Pricing from './components/Pricing.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    PostsExample,
    Contact,
    Pricing
  }
}
</script>

<style>
  @import "../node_modules/bootstrap/dist/css/bootstrap.min.css";

</style>
