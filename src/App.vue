<template>
  <Home />
  <About />
</template>

<script>
import Home from "./components/Home.vue"
import About from "./components/About.vue"

export default {
  name: 'App',
  components: {
    Home,
    About
  }
}
</script>

<style>
* {
  margin: 0;
  padding: 0;
  --bluegray: #3c5078;
  --turq: #1ebee6;
  --blue: #4664ea;
   font-family: "Poppins", sans-serif;
}

#app {
  margin: 0;
  padding: 0;

}
</style>
