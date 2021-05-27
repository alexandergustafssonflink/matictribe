  <template>
     <section id="clients">
         <h1> cases&clients </h1>
         <div class="main">
             <div class="left"> 
        <div class="white client">
            <h3>white</h3>
            <div data-aos="flip-right">
                <img src="/images/white.png" alt="">
                <p class="desc"> Capitalize on low hanging fruit to identify a ballpark value added activity to beta test. Override the digital divide with additional clickthroughs from DevOps. Nanotechnology immersion along the information highway will close the loop on focusing solely on the bottom line. Organically grow the holistic world view of innovation via workplace diversity and empowerment.</p>
            </div>
            <div class="products"> <p>Solution architecture</p><p>Development</p> </div>
        </div>
        <div class="neverbin client">
            <h3>neverbin</h3>
            <div data-aos="flip-right">
                <img src="/images/neverbin.png" alt="">
                <p class="desc"> Neverbin WasteTracker® is a super easy cloud-based service that gives you full control over all products that soon will expire. No integration is needed and it works on all mobile devices. The results vary among stores but store managers state that they spend 50% less personnel on checking expiry dates and they decrease related food waste with 40%. It’s a win-win situation for the grocery store and the environment.</p>
            </div>
            <div class="products"> <p>Solution architecture</p><p>Development</p> </div>
        </div>
       
        </div>
        <div class="right">
              <div class="polestar client">
            <h3>polestar</h3>
            <div data-aos="flip-left">
                <img src="/images/polestar.png" alt="">
                <p class="desc"> Leverage agile frameworks to provide a robust synopsis for high level overviews. Iterative approaches to corporate strategy foster collaborative thinking to further the overall value proposition. </p>
            </div>
            <div class="products"> <p>Solution architecture</p><p>Development</p> </div>
        </div>
         
         <div class="teslajournalen client">
            <h3>teslajournalen</h3>
            <div data-aos="flip-left">
                <img src="/images/teslajournalen.png" alt="">
                <p class="desc"> Leverage agile frameworks to provide a robust synopsis for high level overviews. Iterative approaches to corporate strategy foster collaborative thinking to further the overall value proposition. Organically grow the holistic world view of disruptive innovation via workplace diversity and empowerment.</p>
            </div>
           <div class="products"> <p>Solution architecture</p><p>Development</p> </div>
        </div>
        </div>
         </div>
         <div class="lower">
             <h3> let's see what we can create together
             </h3>
            <div class="services">
                <div><i class="fas fa-server"></i>
                <h4>Solution architecture</h4>
                <p>A description of your competence and offer around your superior solution architecture. </p>
                </div>
                <div><i class="fas fa-terminal"></i>
                 <h4>Development</h4>
                 <p>1337 – a description of your competence and offer around your superior development skillz and haxz. </p>
                </div>
                <div><i class="fas fa-route"></i>
                 <h4>Service Design</h4>
                 <p>We can show you how your business will grow with great service design. </p>
                </div>
                <div><i class="fas fa-rocket"></i>
                <h4>Mentorship as a service</h4>
                <p> A description of your competence and offer around your superior mentorship service.</p>
                </div>
            </div>
         </div>
         <div class="btn-section">
             <a href="#contact"><button class="main-btn"><i class="fas fa-envelope"></i>get in touch </button></a>
         <a href="#contact"><button class="main-btn"><i class="fas fa-calendar-alt"></i>book a digital coffee </button> </a> 
         </div>
    <img class="client-squares" data-aos="fade-left" src="/images/client-squares.svg" alt="">
    </section>

</template>

<script>
export default {
  name: 'Clients',
  props: {
  },
  
}
</script>


<style scoped>
#clients {
  background-color:var(--blue);
    padding-bottom: 300px; 
  position: relative;


}

.main {
    padding: 0px 200px 0px 200px; 
    display: flex; 
    justify-content: space-between;
}

h1 {
    font-size: 100px; 
    color: white; 
    font-weight: 700; 
    padding: 50px 0px 0px 200px;
}

.client {
    max-width: 30em;  
} 

.client img {
    width: 100%; 
    margin-bottom: -6px; 
}

.client h3 {
    font-size: 60px; 
    font-weight: 700;
}

.client .desc {
    padding: 20px; 
    font-size: 20px; 
    font-weight: 300;
    
}

.products {
    display: flex; 
    margin-top: 5px; 
 
}
.products p {
    padding: 5px 10px 5px 10px;  
    margin-right: 5px; 
     font-weight: 700; 
}
.white h3 {
    color: var(--turq);
   
}

.white .desc {
     background-color: var(--turq);
     color: white; 
}

.white .products p {
     background-color: var(--turq);
     color: white; 
}
.polestar h3 {
    color: #FAD250; 
}
.polestar .desc{
    background-color: #FAD250; 
    color: var(--bluegray); 
}

.polestar .products p {
     background-color: #FAD250; 
     color: var(--bluegray); 
}

.neverbin h3 {
    color: #FF87A0; 
      margin-top: 50px; 
}
.neverbin .desc {
    background-color: #FF87A0;
    color: var(--bluegray); 
}

.neverbin .products p {
     background-color: #FF87A0;
     color: var(--bluegray); 
}

.teslajournalen h3 {
    color: #82DCA0; 
    margin-top: 50px; 
}
.teslajournalen .desc {
    background-color: #82DCA0;
    color: var(--bluegray); 
}
.teslajournalen .products p {
     background-color: #82DCA0;
     color: var(--bluegray); 
}

.lower {
    padding: 100px 200px 0px 200px; 
}
.lower h3 {
    color: white; 
    font-size: 50px; 
    font-weight: 700;
    width: 50%; 
    letter-spacing: -3px; 
    line-height:42px;
}


.services {
    display: flex; 
    justify-content: space-between;
    margin-top: 50px; 
}
.services i {
    font-size: 40px; 
    color: white; 
    margin-bottom: 15px; 
}
.services h4 {
    font-size: 24px; 
    color: white; 
     margin-bottom: 15px; 

}
.services p {
    color: white; 
}

.services div {
    width: 15em; 
}

.client-squares {
    position: absolute; 
    bottom: 0px;
    right: 0px; 
    width: 25%; 
}

.btn-section {
    margin: 50px 0px 0px 200px; 

}

.main-btn {
    border: none; 
    background-color: #6b83ee; 
    color: white; 
    padding: 10px 20px 10px 20px; 
    font-size: 18px; 
    font-weight: 700; 
    margin-right: 15px; 
    cursor: pointer

}

.main-btn i {
    margin-right: 10px; 
}


@media only screen and (max-width: 799px) {
.main {
    padding: 0px 30px 0px 30px; 
    flex-direction: column;
}
h1 {
    padding: 30px 30px 0px 30px; 
    font-size: 40px; 
    
}

.client h3 {
    font-size: 40px; 
    margin-top: 30px; 
}

.lower{
    padding: 50px 30px 0px 30px; 
}

.lower h3  {
    width: 100%; 
    font-size: 36px; 
    letter-spacing: -2px;
}

.services {
    flex-direction: column;
}

.services div {
    margin-bottom: 50px; 
}

.btn-section {
    margin: 30px 30px 0px 30px; 
}

.main-btn {
    margin-bottom: 15px; 
}

.client-squares {
    width: 75%; 
}
}


@media only screen and (min-width: 500px)and (max-width: 799px)  {
    h1 {
        margin-left: 45px; 
        font-size: 60px; 
    }
    .main {
        margin: 0px 45px 0px 45px; 
    }

    .lower{
        margin: 0px 45px 0px 45px; 
    }

    .services {
        flex-flow: wrap;
    }

    .client-squares {
        width: 40%; 
    }

    .btn-section {
        margin-left: 75px; 
    }
}
</style>