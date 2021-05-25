  <template>
     <section id="contact">   
         <h1> Contact </h1>
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

    <img src="/images/contact-image.svg" alt="">

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

#contact h1 {
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





</style>