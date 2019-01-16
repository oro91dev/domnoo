<template>
  <div>

    <comp-header></comp-header>
    <div>
      <comp-featured></comp-featured>
      <comp-menu></comp-menu>
      <comp-call-us></comp-call-us>
      <comp-newsletter></comp-newsletter>
    </div>
    <comp-footer></comp-footer>


  </div>
  
</template>

<script>

import compHeader from './components/Header/Header.vue';
import compFooter from './components/Footer/Footer.vue';
import compFeatured from './components/Featured/index.vue';
import compMenu from './components/Menu/index.vue';
import compCallUs from './components/CallUs/index.vue';
import compNewsletter from './components/Newsletter/index.vue';

export default {
  components:{
    compHeader,
    compFooter,
    compFeatured,
    compMenu,
    compCallUs,
    compNewsletter
  }
}
</script>

<style>
  @import './assets/style.css';
</style>



