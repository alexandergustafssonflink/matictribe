<template>
<BurgerMenu />
  <Home />
  <About />
  <Clients />
  <Career />
  <Contact />
  <Footer />
 
</template>

<script>
import Home from "./components/Home.vue"
import BurgerMenu from "./components/BurgerMenu.vue"
import About from "./components/About.vue"
import Clients from "./components/Clients.vue"
import Career from "./components/Career.vue"
import Contact from "./components/Contact.vue"
import Footer from "./components/Footer.vue"


export default {
  name: 'App',
  components: {
    Home,
    BurgerMenu,
    About,
    Clients,
    Career,
    Contact,
    Footer
   
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
