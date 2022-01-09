<template>
  <Navbar />
  <router-view/>
</template>

<script>
import Navbar from "./components/Navbar.vue"

export default {
  components: { Navbar }
}
</script>

<style>
#app {
  text-align: center;
  color: #2c3e50;
  font-family: 'Lato', sans-serif;
  font-family: 'Rubik', sans-serif;
}
body {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>
