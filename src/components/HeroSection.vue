<template>
  <div class="container">
    <h1 class="header-title">Isaac Hernández.</h1>
    <h2 class="sub-header">Bulding things for the new web.</h2>
    <p class="text">
      I'm a passinate and young developer, focused on web 3 development. <br />
      Wishing to make fun and useful stuff for you. Let's do this!
    </p>
    <button class="btn-hero">Say Hi!</button>
  </div>
</template>


<style scope>

/**Desktop */
.container {
  display: flex;
  flex-direction: column;
  flex-wrap: wrap;
  justify-content: flex-start;
  align-items: flex-start;
  position: relative;
  left: 10%;
}

@media screen and (min-width: 12.5em) and (max-width: 31.25em) {

  .container {
    padding-right: 40px;
  }
}



/**Desktop */
.header-title {
  font-family: "Inter", sans-serif;
  font-size: 84px;
  color: #64ffda;
  margin-bottom: 10px;
  margin-top: 10%;
}

/**Mobile */
@media screen and (min-width: 12.5em) and (max-width: 31.25em) {

  .header-title {
    font-size: 44px;
    padding-right: 20px;
  }
}

/**Tablet */
@media screen and (min-width: 31.25em) and (max-width:  56.25em) {

  .header-title {
    font-size: 64px;
    padding-right: 20px;
  }
}

.header-title:hover {
  color: #ccd6f6;
}

/**Desktop */
.sub-header {
  font-family: "Inter", sans-serif;
  font-size: 64px;
  color: #a8b2d1;
  margin-bottom: -5px;
  margin-top: -10px;
}

/**Mobile */
@media screen and (min-width: 12.5em) and (max-width: 31.25em) {

  .sub-header {
    font-size: 24px;
    padding-right: 20px;
  }
}

/**Tablet */
@media screen and (min-width: 31.25em) and (max-width:  56.25em) {

  .sub-header {
    flex-wrap: wrap;
    font-size: 44px;
    padding-right: 20px;
  }
}

/**Desktop */
.text {
  font-family: "Inter", sans-serif;
  font-size: 16px;
  font-style: bold;
  color: #a8b2d1;
  font-weight: normal;
  margin-bottom: 30px;
}

/**Mobile */
@media screen and (min-width: 12.5em) and (max-width: 31.25em) {

  .text {
    font-size: 10px;
    padding-right: 20px;
  }
}

/**Tablet */
@media screen and (min-width: 31.25em) and (max-width:  56.25em) {

  .text {
    flex-wrap: wrap;
    font-size: 14px;
    padding-right: 20px;
  }
}

/**Desktop */
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

/**Mobile */
@media screen and (min-width: 12.5em) and (max-width: 31.25em) {

  .btn-hero {
    font-size: 8px;
    width: 40%;
    padding: 10px;
  }
}

/**Tablet */
@media screen and (min-width: 31.25em) and (max-width:  56.25em) {

  .btn-hero {
    font-size: 12px;
    width: 30%;

  }
}

.btn-hero:hover {
  color: #a8b2d1;
  border-color: #a8b2d1;

}
</style>
