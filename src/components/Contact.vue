  <template>
     <section id="contact">   
         <h1 data-aos="fade-right"> Contact </h1>
        <div className="form-div">
      <form action="/email" className="contact-form" method="get">
      <label for="email">Mail</label>
        <input type="text" id="email" name="email" />
        <label for="message">Message</label>
        <input
          type="text"
          id="message"
          name="message"
        />
        <input type="submit" className="submit-btn" value="send" />
      </form>
    </div>

    <img alt="squares" src="/images/contact-image.svg" data-aos="fade-left">

     </section>
</template>

<script>

export default {
  name: 'Contact',
  props: {
  },

}
</script>


<style scoped>
#contact {
   background-color: var(--turq);
   height: 100vh; 
   position: relative
}
#contact img {
    position: absolute;
    bottom: 0px; 
    right: 10rem; 
    width: 32%; 
}

h1 {
    font-size: 80px; 
    padding: 100px 0px 0px 200px; 
    color: white; 
    font-weight: 700;
}
.contact-form {
  display: flex;
  flex-direction: column;
}

.form-div {
  width: 20%;
  margin-left: 200px; 
  margin-top: 150px;
  font-size: 28px;
  color: var(--beige);
  position: relative;
}
.form-div label {
    color: white; 
    font-size: 20px; 
}

.contact-form input {
  background: none;
  border: none;
  font-size: 24px;
  margin-bottom: 30px;
  padding: 10px;
}

.contact-form #message {
  color:white; 
  border-bottom: solid 2px white; 
}

.contact-form #email {
  color:white; 
  border-bottom: solid 2px white; 
}





.submit-btn {
  width: 100%; 
  text-align: right; 
  color: white; 
  font-size: 60px !important; 
  font-weight: 700;
}

@media only screen and (max-width: 500px) {
    h1 {
        font-size: 40px; 
        padding: 50px 0px 0px 30px; 
    }

    .form-div {
        padding: 50px 30px 0px 30px; 
        margin: 0px; 
        width: auto; 
    }
    .contact-form .submit-btn {
        font-size: 24px !important; 
    }

    #contact img {
        width: 90%; 
        right: 0;
    }

    #contact {
        height: 140vh; 
    }
    
}

@media only screen and (min-width: 500px)and (max-width: 799px)  {
    h1 {
        padding: 50px 0px 0px 75px; 
        font-size: 60px; 
    }

    .form-div {
        margin-left: 75px; 
        width: 50%; 
    }

  #contact img {
        right: 0px;
        width: 50%
    }

  .contact-form  .submit-btn {
        font-size: 40px !important; 
        padding-right: 0px; 
    }
}



</style>