  <template>
     <section id="career">   
         <div class="upper-div">
        <div class="left"><img class="office-img" data-aos="zoom-in-up" src="/images/Office.png" alt="Office image"></div>
        <div class="right">
            <h1>career</h1>
            <div class="left"><img class="office-mobile-img" data-aos="zoom-in-up" src="/images/Office.png" alt="Office image"></div>
            <p class="lead"> We are always on the lookout for new and inspiring talent, please send us a mail or book a video call and we’ll see what we can do together. </p>
             <div class="btn-section">
         <a href="#contact"><button class="main-btn"><i class="fas fa-envelope"></i>get in touch </button></a> <a href="#contact"><button class="main-btn"><i class="fas fa-calendar-alt"></i>book a digital coffee </button> </a> 
         </div>
        </div>
         </div>
         <div class="lower-div">
            <h2>right now we are particularly interested in </h2>
            <div class="job-section">
            <div class="job" data-aos="zoom-out"><div class="job-header"><img src="/images/circle.svg" alt="circle image"><h3>job title </h3></div><p>Est dolor in aliqua ullamco Lorem ut ea excepteur minim dolor ex duis. Cillum pariatur et Lorem nisi. </p></div>
            <div class="job" data-aos="zoom-out"><div class="job-header"><img src="/images/triangle.svg" alt="triangle image"><h3>job title </h3></div><p>Est dolor in aliqua ullamco Lorem ut ea excepteur minim dolor ex duis. Cillum pariatur et Lorem nisi. </p></div>
            <div class="job" data-aos="zoom-out"><div class="job-header"><img src="/images/square.svg" alt="square image"><h3>job title </h3></div><p>Est dolor in aliqua ullamco Lorem ut ea excepteur minim dolor ex duis. Cillum pariatur et Lorem nisi. </p></div>
            </div>
         </div>

     </section>
</template>

<script>

export default {
  name: 'Career',
  props: {
  },

}
</script>


<style scoped>
#career {
    color: var(--blue); 
    font-weight: 700; 
    overflow: hidden;
}

.upper-div {
    padding: 100px 200px 100px 200px;  
    display: flex; 
    justify-content: space-between;
}



.left {
    width: 48%; 
}

.left img {
    width:100%; 
}
.right {
    width: 48%; 
    position: relative
}
h1 {
    font-size: 100px; 
}

.btn-section {

}

.main-btn {
    border: none; 
    background-color: #e3e8fd; 
    color: var(--blue);  
    padding: 10px 20px 10px 20px; 
    font-size: 18px; 
    font-weight: 700;
    margin-right: 20px; 
    cursor: pointer; 

}

.main-btn i {
    margin-right: 10px; 
}

.lead {
    font-size: 18px; 
}

.btn-section {
margin-top: 50px;
}

.lower-div {
   padding: 50px 200px 0px 200px; 
 
}

h2 {
    font-size: 24px; 
    font-weight: 700; 
}

.job-section {
    display: flex; 
    justify-content: space-between;
    margin-top: 30px;
    padding-bottom: 100px; 
}

.job {
    margin: 15px;
}

.job-header {
    position:relative; 
    height: 150px; 
}
.job-header img {
    height:100%; 
}

.job p {
    font-size: 18px;
    font-weight: 400;
    margin-top: 20px;
}

h3 {
    position: absolute;
    top: 50%; 
    right: 45%; 
    font-size: 24px;
}

   .office-img {
       
       display: block; 
    }

    .office-mobile-img {
      
         display: none; 
    }

@media only screen and (max-width: 500px) {
    h1 {
        font-size: 40px; 
    }
    .upper-div {
        padding: 50px 30px 0px 30px; 
        flex-direction: column; 
    }
    .right {
        width: 100%; 
    }
    .left {
        width: 100%; 
    }

    .lower-div {
        padding: 50px 30px 0px 30px; 
    }

    .job-section {
        flex-direction: column;
        padding-bottom: 50px; 
    }

    .job {
        margin: 0px 0px 50px 0px; 
    }

    .office-img {
        display: none; 
    }

    .office-mobile-img {
        display: block; 
        padding: 30px 0px 30px 0px;
    }

    .btn-section {
        margin-top: 30px; 
    }

    .main-btn {
        margin-top: 10px; 
    }
}

@media only screen and (min-width: 500px)and (max-width: 799px)  {
    .upper-div {
        padding: 50px 75px 50px 75px; 
    }

    .right h1 {
        font-size: 60px; 
    }
    .btn-section :nth-child(2) {
        margin-top: 15px; 
    }

    .lower-div {
        padding: 50px 75px 0px 75px; 
    }
    .job h3 {
        right: 0%; 
    }
}

</style>