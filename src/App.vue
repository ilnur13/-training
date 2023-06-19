<script setup>
import Header from './components/Layout/Header.vue'
import Hero from './components/Layout/Hero.vue'
import AboutBrand from './components/Layout/AboutBrand.vue'
import Products4Column from './components/Layout/Products4Column.vue'
import Ideas from './components/Layout/Ideas.vue'
import Subscribe from './components/Layout/Subscribe.vue'
import Footer from './components/Layout/Footer.vue'
</script>

<template>
  <div class="container">
    <Header/>
    <Hero />
    <AboutBrand />
    <Products4Column />
    <ideas/>
    <Subscribe/>
    <Footer/>
  </div>
</template>

<style lang="scss">
@import url('https://fonts.cdnfonts.com/css/satoshi');
@import url('https://fonts.cdnfonts.com/css/clash-display');
* {
  box-sizing: border-box;
}
body{
  margin: 0;
  padding: 0;
  font-family: 'Clash Display', sans-serif;
  font-family: 'Satoshi', sans-serif;
  font-size: 16px;
}
.container{
  max-width: 1440px;
  margin: auto;
}
</style>
