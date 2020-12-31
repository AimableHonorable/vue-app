<template>
  <div id="app">
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
  <a class="navbar-brand" href="#">Navbar</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarNav">
    <ul class="navbar-nav">
      <li class="nav-item active">
        <router-link class="nav-link" :to="'/'">Home <span class="sr-only">(current)</span></router-link>
      </li>
      <li class="nav-item">
        <router-link class="nav-link" :to="'/contact'">Contact</router-link>
      </li>
      <li class="nav-item">
        <router-link class="nav-link" :to="'/pricing'">Pricing</router-link>
      </li>
      <li class="nav-item">
        <a class="nav-link disabled" href="#" tabindex="-1" aria-disabled="true">Disabled</a>
      </li>
    </ul>
  </div>
</nav>
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
