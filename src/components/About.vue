  <template>
   <section id="about">
     <div class="main">
     <div class="left">
     <h1> about</h1>
        <p>
      Open-minded software agency that fancy sleek design and lightweight processes.
      </p>
      <br>
      <p class="light-text">
         We strive for full transparency and are passionate about solving problems in the real world. Not the made-up problems, the real ones. Our complete skill set makes it possible to lead business development decisions, through a well thought out architecture, to final verified code.
         <br><br>We work with a network of professionals to ensure that we always can help our customers solve all of their problems, the real ones.
        <br><br> Business needs can not come closer to the keyboard. 
      </p>
      </div>
      <div class="right">
      <img src="../assets/images/squares.svg" />
      </div>
      </div>
      <div class="lower-main">
        <PeopleCard name="calle rynning" email="carl@matictribe.com" title="solutions architect" img='/images/calle.png' />
        <PeopleCard name="martin lannsjö" email="martin@matictribe.com" title="solutions architect" img='images/martin.png' />
        <PeopleCard name="andreas ericsson" email="anderas@matictribe.com" title="lead developer" img="/images/andreas.png" />
        <PeopleCard name="jens kjellerup" email="jens@matictribe.com" title="business designer" img="/images/jens.png" />
        <PeopleCard name="markus barett" email="markus@matictribe.com" title="fullstack developer" img="/images/markus.png" />
     
      </div>
    <img class="circles" src="/images/circles.svg" />
    </section>
</template>

<script>
import PeopleCard from "./PeopleCard.vue"

export default {
  name: 'About',
  props: {
  },
   components: {
     PeopleCard,
  },

}
</script>


<style scoped>
#about {
  height: 180vh;
  background-color: var(--turq);
  position: relative;
  z-index: -1; 
  overflow: hidden; 
}

.main {
  margin: 0px 200px 0px 200px;
  color: white;
  display: flex;
  padding-top: 100px;
  justify-content: space-between;
  position: relative;
  z-index: 1; 
}

.main h1 {
  font-size: 100px;
  margin-top: -20px; 
}

.main .left {
  width: 48%;
}

.light-text {
  opacity: 0.8;
}

 .main .right {
  width: 48%;
}

.right img {
    width: 100%; 
}

.lower-main {
  padding: 50px 50px 100px 150px;
  width: 100%; 
  display: flex;
  flex-flow: wrap;
  position: relative;
  z-index: 1; 
}
.circles {
    position: absolute; 
    bottom: 0px;
    width: 90%; 
}

</style>