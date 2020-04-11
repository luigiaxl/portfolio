<template>
  <div
    id="app"
    class="h-full flex flex-col md:flex-row"
  >
    <AboutMe class="w-full md:w-2/6"></AboutMe>

    <div class="flex-1 py-10">
      <div>
        <router-link :to="{name: 'home'}">Home</router-link> |
        <router-link :to="{name: 'projects'}">Projects</router-link> |
        <router-link :to="{name: 'skills'}">Skills</router-link> |
        <router-link :to="{name: 'about'}">About Me</router-link>
      </div>
      <router-view/>
    </div>
  </div>
</template>

<script>
  import AboutMe from './components/about_me/AboutMe.vue'

  const components = {
    AboutMe
  }

  export default {
    components
  }
</script>

<style>
  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
  }
</style>