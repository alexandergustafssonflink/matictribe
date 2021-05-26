  <template>
     <section id="home">
         <Navbar />
     <img class="triangles-upper" src="/images/upper-triangles.png" />
     <img class="triangles-bottom" src="/images/bottom-triangles.png" />
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
  width: 100vw; 
}

 h1 {
  font-size: 80px;
  color: var(--bluegray);
}

.main {
  position: absolute;
  margin-left: 200px; 
  bottom: 60%;
}

.main p {
  font-size: 20px;
  color: var(--bluegray);
}

.triangles-bottom {
  right: 0px;
  width: 85%;
  position: absolute;
  bottom: -20px;
}

.triangles-upper {
  position: absolute;
  top: 0px;
  right: 6%;
  width: 35em; 
}

@media only screen and (max-width: 500px) {
  #home .triangles-upper {
    right: -70%; 
  }

  .triangles-bottom {
  
    right: -142%; 
    width: 1120px; 
  }

  .main {
    margin: 30px; 
    bottom: 55%; 
  }

  h1 {
    font-size: 36px; 
  }
}

@media only screen and (min-width: 500px)and (max-width: 799px)  {
  h1 {
    font-size: 60px; 
  }
  .main {
    margin-right: 75px; 
    margin-left: 75px; 
    bottom: 50%; 
  }
}
</style>