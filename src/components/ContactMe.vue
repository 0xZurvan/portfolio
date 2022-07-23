<template>
    <div class="contact-container">
      <h4 class="sub-heading">What are you waiting for?</h4>
      <h3 class="heading"> ¡ Don't get shy !</h3>
      <button class="btn">Say Hi!</button>
    </div>
</template>

<style scoped>

.contact-container {
  display: inline-flex;
  box-sizing: border-box;
  flex-direction: column;
  align-items: center;
  margin-bottom: 15%;
}

.contact-container .sub-heading {
  font-family: "Inter", sans-serif;
  font-size: 18px;
  font-weight: normal;
  font-style: bold;
  color: #64ffda;
  margin-top: 15%;
}

.contact-container .heading {
  display: flex;
  width: 100%;
  justify-content: space-around;
  font-family: "Inter", sans-serif;
  font-size: 42px;
  color: #ccd6f6;
  position: relative;
  top: -50px;
}

.heading::before {
  content: "";
  width: 30%;
  margin-left: 10px;
  position: relative;
  bottom: 18px;
  border-bottom: 1px solid #ccd6f6;
  opacity: 0.5;
}

.heading::after {
  content: "";
  width: 30%;
  margin-right: 10px;
  position: relative;
  bottom: 18px;
  border-bottom: 1px solid #ccd6f6;
  opacity: 0.5;
}

.contact-container .heading:hover {
  color: #64ffda;
}

.contact-container .btn {
  font-family: 'Inter', sans-serif;
  background-color: #112240;
  font-size: 14px;
  color: #64ffda;
  border-color: #64ffda;
  width: 20%;
  padding: 15px;
  border-radius: 5px;
  position: relative;
  top: -50px;
}

.contact-container .btn:hover {
  color: #a8b2d1;
  border-color: #a8b2d1;

}

</style>