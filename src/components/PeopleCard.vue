  <template>
      <div class="people-card">
        <img :src="img">
        <h3 class="name">{{name}} </h3>
        <h3 class="title"> {{title}} </h3>
        <p> {{email}} </p>
      </div>
</template>

<script>

export default {
  name: 'PeopleCard',
    props: {
       img: String, 
       name: String,
       title: String,
       email: String
       },
}
</script>


<style scoped>

.people-card {
  margin: 0px 50px 50px 50px; 
  min-width: 300px;
}

.title {
    font-size: 24px; 
    color: white; 
    font-weight: 700; 
    opacity: 0.6; 
    letter-spacing: -0.04em;
}

.name {
    color: white; 
font-style: normal;
font-weight: bold;
font-size: 24px;
line-height: 24px;
}

p {
    font-weight: bold; 
    color: White; 
}

.light-text {
  opacity: 0.8;
}


</style>