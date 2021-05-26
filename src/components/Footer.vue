  <template>
     <div class="footer">   
         <div class="contact-card">
         <h3> []matic tribe </h3>
         <p>Orgnr: 559182-6770<br>
            Vallgatan 25, 411 16 Göteborg<br>
            hello@matictribe.com
            </p>
        </div>
        <div class="social">
            <i class="fab fa-facebook-square"></i>
            <i class="fab fa-instagram-square"></i>
            <i class="fab fa-linkedin"></i>
        </div>

     </div>
</template>

<script>

export default {
  name: 'Footer',
  props: {
  },

}
</script>


<style scoped>
.footer {
height: 300px;
background-color: var(--bluegray);
display: flex; 
justify-content: space-between;
}

.social {
    margin:50px 200px 0px 0px;
}

.social i {
    font-size: 36px;
    color: white; 
    margin: 16px; 
}

.contact-card {
    color: white; 
    padding: 50px 0rem 0px 200px; 
}

h3 {
    font-size: 36px; 
    margin-bottom: 15px; 
}
p {
    font-weight:400;
    font-size: 14px; 
}

@media only screen and (max-width: 500px) {
    .footer {
        flex-direction: column;
        justify-content: unset;
    }
    .social {
        margin: 30px 30px 0px 15px; ; 
    }
    .contact-card  {

        padding: 50px 30px 0px 30px; 
    }
}

@media only screen and (min-width: 500px)and (max-width: 799px)  {
 
    .contact-card {
        padding: 50px 0px 0px 75px; 
        
    }

    .social {
        margin-right: 75px; 
    }
}



</style>