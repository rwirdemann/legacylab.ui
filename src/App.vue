<template>
  <div id="app">
    <section class="section">
      <div class="container">
        <h1 class="title">
          Hello World
        </h1>
        <p class="subtitle">
          My first website with <strong>Bulma</strong>!
        </p>
      </div>
    </section>
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
