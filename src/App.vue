<template>
  <div id="app">    
    <section class="section">
      <div class="container">
        <h1 class="title">LegacyLab Projects</h1>
      <HelloWorld name="CoRE-DS" url="https://devstack.vwgroup.com/bitbucket/scm/ngw/vwg.idhub.core-ds.git" />
      <HelloWorld name="Docker" url="https://github.com/docker/docker-ce.git" />
      </div>
    </section>
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
