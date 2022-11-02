<template>
  <div id="app">

    <header-comp />
    <main-comp />
    <footer-comp />

  
  </div>
</template>

<script>
import HeaderComp from './components/HeaderComp.vue';
import FooterComp from './components/FooterComp.vue';
import MainComp from './components/MainComp.vue';

export default {
  name: 'App',
  components: {
    HeaderComp,
    FooterComp,
    MainComp,
  }
}

</script>

<style>

</style>
