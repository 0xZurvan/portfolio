<template>
  <div class="container">
    <h1 class="header-title">Isaac Hernández.</h1>
    <h2 class="sub-header">Bulding things for the new web.</h2>
    <p class="text">
      I'm a passinate and young developer, focused on web 3 development. <br />
      Wishing to make fun and useful stuff for you. Let's do this!
    </p>
    <button class="btn-hero">Get in touch</button>
  </div>
</template>


<style scope>

.container {
  display: flex;
  flex-direction: column;
  flex-wrap: wrap;
  justify-content: flex-start;
  align-items: flex-start;
  position: relative;
  left: 10%;
}

.header-title {
  font-family: "Inter", sans-serif;
  font-size: 84px;
  color: #64ffda;
  margin-bottom: 10px;
  margin-top: 10%;
}

.header-title:hover {
  color: #ccd6f6;
}

.sub-header {
  font-family: "Inter", sans-serif;
  font-size: 64px;
  color: #a8b2d1;
  margin-bottom: -5px;
  margin-top: -10px;
}

.text {
  font-family: "Inter", sans-serif;
  font-size: 16px;
  font-style: bold;
  color: #a8b2d1;
  font-weight: normal;
  margin-bottom: 30px;
}

.btn-hero {
  font-family: 'Inter', sans-serif;
  font-size: 16px;
  background-color: #112240;
  color: #64ffda;
  border-color: #64ffda;
  width: 20%;
  padding: 20px;
  position: relative;
  top: 10%;
  border-radius: 5px;
}

.btn-hero:hover {
  color: #a8b2d1;
  border-color: #a8b2d1;

}
</style>
