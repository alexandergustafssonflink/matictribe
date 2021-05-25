  <template>
     <section id="home">
         <Navbar />
     <img class="triangles-upper" src="../assets/images/upper-triangles.png" />
     <img class="triangles-bottom" src="../assets/images/bottom-triangles.png" />
     <div class="main">
      <h1> [] matic tribe</h1>
      <p> a pragmatic, transparent, get-it-done enabler of digital products and services. </p>
      </div>
   
    </section>
</template>

<script>
import Navbar from "./Navbar.vue"
export default {
  name: 'Home',
  props: {
  },
  components: {
      Navbar,
  }
}
</script>


<style scoped>
#home {
  background-color: white;
  height: 100vh;
  position: relative;
  overflow: hidden;
}

#home h1 {
  font-size: 80px;
  color: var(--bluegray);
}

#home .main {
  position: absolute;
  margin-left: 200px; 
  bottom: 60%;
}

#home .main p {
  font-size: 20px;
  color: var(--bluegray);
}

#home .triangles-bottom {
  right: 0px;
  width: 85%;
  position: absolute;
  bottom: -20px;
}

#home .triangles-upper {
  position: absolute;
  top: 0px;
  right: 6%;
  width: 35em; 
}
</style>