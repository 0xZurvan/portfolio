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

/**Desktop */
.contact-container .sub-heading {
  font-family: "Inter", sans-serif;
  font-size: 18px;
  font-weight: normal;
  font-style: bold;
  color: #64ffda;
  margin-top: 15%;
}

/**Mobile */
@media screen and (min-width: 12.5em) and (max-width: 31.25em) {

  .contact-container .sub-heading {
    font-size: 10px;
  }
}

/**Tablet */
@media screen and (min-width: 31.25em) and (max-width:  56.25em) {

  .contact-container .sub-heading {
    font-size: 15px;
    padding-right: 20px;
  }
}

/**Desktop */
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

/**Mobile */
@media screen and (min-width: 12.5em) and (max-width: 31.25em) {

  .contact-container .heading {
    font-size: 20px;
    top: -30px;
    margin-bottom: 20px;
  }
}

/**Tablet */
@media screen and (min-width: 31.25em) and (max-width:  56.25em) {

  .contact-container .heading {
    font-size: 32px;
    padding-right: 20px;
  }
}

/**Desktop */
.heading::before {
  content: "";
  width: 30%;
  margin-left: 10px;
  position: relative;
  bottom: 18px;
  border-bottom: 1px solid #ccd6f6;
  opacity: 0.5;
}

/**Mobile */
@media screen and (min-width: 12.5em) and (max-width: 31.25em) {

  .heading::before {
    width: 20%;;
  }
}

/**Desktop */
.heading::after {
  content: "";
  width: 30%;
  margin-right: 10px;
  position: relative;
  bottom: 18px;
  border-bottom: 1px solid #ccd6f6;
  opacity: 0.5;
}

/**Mobile */
@media screen and (min-width: 12.5em) and (max-width: 31.25em) {

  .heading::after {
    width: 20%;
  }
}

.contact-container .heading:hover {
  color: #64ffda;
}

/**Desktop */
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

/**Mobile */
@media screen and (min-width: 12.5em) and (max-width: 31.25em) {

  .contact-container .btn {
    font-size: 8px;
    width: 40%;
    padding: 10px;
    position: relative;
    top: -30px;
  }
}

/**Tablet */
@media screen and (min-width: 31.25em) and (max-width:  56.25em) {

  .contact-container .btn {
    font-size: 12px;
    width: 30%;

  }
}

.contact-container .btn:hover {
  color: #a8b2d1;
  border-color: #a8b2d1;

}

</style>