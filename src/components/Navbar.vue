<template>
    <nav>
        <ul>
            <li> <a href="/#about">about </a>  </li>
            <li><a href="/#clients">cases & clients</a>  </li>
            <li><a href="/#career">career</a>  </li>
            <li><a href="/#contact">contact</a>  </li>
        </ul>
    </nav>
</template>
  

<script>
export default {
  name: 'Navbar',
  props: {
  }
}
</script>

   <style scoped>
    nav {
  color: var(--turq);
  font-weight: 700;
  position: absolute;
  z-index: 100;
  margin-left: 200px; 
  width: auto;
  overflow: hidden;
}

nav ul {
  list-style: none;
  display: flex;
  justify-content: space-between;
  font-size: 24px;
}
nav li {
  padding: 20px 30px 0px 0px;
  
}
 a{
   text-decoration: none;
   color: var(--turq); 
  -webkit-transition: all 0.2s ease-in;
-moz-transition: all 0.2s ease-in;
-o-transition: all 0.2s ease-in;
transition: all 0.2s ease-in;
   
 }

 a:hover {
   color: var(--bluegray);
 }

@media only screen and (max-width: 799px) {
  nav {
    display: none; 
  }

}
   </style>