<template>
  <Navbar />
  <HeroSection />
  <Projects />
  <ContactMe />
  <Footer />
</template>

<script setup>
import HeroSection from "@/components/HeroSection.vue";
import Projects from "@/components/Projects.vue";
import Navbar from "@/components/Navbar.vue";
import ContactMe from "@/components/ContactMe.vue";
import Footer from "@/components/Footer.vue";
</script>

<style>
/**Title */
@import url("https://fonts.googleapis.com/css2?family=Inter:wght@800&display=swap");

/**Project names */
@import url("https://fonts.googleapis.com/css2?family=Inter:wght@100&display=swap");

/**Text */
@import url("https://fonts.googleapis.com/css2?family=Inter:wght@300&display=swap");

html,
body {
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
