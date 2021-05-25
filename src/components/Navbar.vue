<template>
    <nav>
        <ul>
            <li>about </li>
            <li>cases & clients </li>
            <li>career </li>
            <li>contact </li>
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
   </style>