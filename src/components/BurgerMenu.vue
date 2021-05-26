<template>
    <Slide>
      <a href="/#about"> 
        <span>about</span>  
      </a>
       <a href="#clients"> 
        <span>cases & clients</span>  
      </a>
       <a href="/#career"> 
        <span>career</span>  
      </a>
       <a href="/#contact"> 
        <span>contact</span>  
      </a>
    </Slide>
</template>


<script>
import { Slide } from 'vue3-burger-menu'  // import the CSS transitions you wish to use, in this case we are using `Slide`

export default {
    name: 'BurgerMenu',
    components: {
        Slide // Register your component
    }
}
</script>


<style>
.bm-burger-button {
    z-index: 1000; 
      position: fixed !important;
      width: 36px;
      height: 30px;
      left: 36px;
      top: 36px;
      cursor: pointer;
    }
    .bm-burger-bars {
      background-color: #373a47;
    }
    .line-style {
      position: absolute;
      height: 20%;
      left: 0;
      right: 0;
    }
    .cross-style {
      position: absolute;
      top: 30px;
      left: 34px;
      cursor: pointer;
    }
    .bm-cross {
      background: #bdc3c7;
    }
    .bm-cross-button {
      height: 24px;
      width: 24px;
    }
    .bm-menu {
      height: 100%; /* 100% Full-height */
      width: 0; /* 0 width - change this with JavaScript */
      position: fixed; /* Stay in place */
      z-index: 1001; /* Stay on top */
      top: 0;
      left: 0;
      background-color: var(--bluegray);/* Black*/
      overflow-x: hidden; /* Disable horizontal scroll */
      padding-top: 60px; /* Place content 60px from the top */
      transition: 0.2s; /*0.5 second transition effect to slide in the sidenav*/
    }

    .bm-overlay {
      background: rgba(0, 0, 0, 0.3);
    }
    .bm-item-list {
      color: #b8b7ad;
      margin-left: 30px; 
      font-size: 20px;
    }
    .bm-item-list > * {
      display: flex;
      text-decoration: none;
      padding: 12px 0px 12px 0px; 
    }
    .bm-item-list > * > span {
      margin-left: 0px; 
      font-weight: 700;
      color: white;
      font-size: 24px; 
    }


    @media only screen and (min-width: 799px) {
        .bm-burger-button {
            display: none; 
        }

    }
</style>