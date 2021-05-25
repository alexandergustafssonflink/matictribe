  <template>
     <div class="footer">   
         <div class="contact-card">
         <h3> []matic tribe </h3>
         <p>Orgnr: 559182-6770<br>
            Vallgatan 25, 411 16 Göteborg<br>
            hello@matictribe.com
            </p>
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
height: 250px;
background-color: var(--bluegray);
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




</style>