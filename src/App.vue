<template>
<Navbar />
<HeroSection />
<Projects /> 

</template>

<script setup>
import HeroSection from '@/components/HeroSection.vue'    
import Projects from '@/components/Projects.vue'  
import Navbar from '@/components/Navbar.vue'  

</script>

<style>


html, body {
  height: 100%;
  width: 100%;
  margin: 0;
  padding: 0;
  overflow-x: hidden;
}

#app {
  display: flex;
  flex-direction: column;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  background-color: #0a192f;
  min-width: 100%;
  min-height: 100%;
}
</style>
