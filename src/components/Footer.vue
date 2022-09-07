<template>
  <div class="footer">
    <p class="copyright">Built by Isaac Hernández</p>
    <email>isaachernandezeseverino@gmail.com</email>
  </div>
</template>


<style scoped>

/**Desktop */
.footer {
  display: flex;
  box-sizing: border-box;
  justify-content: space-around;
  align-items: baseline;
  padding: 20px 0px 5px 0px;
}

/**Mobile */
@media screen and (min-width: 12.5em) and (max-width: 31.25em) {

  .footer {
    flex-direction: column;
    align-items: center;
    margin: 10px auto;

  }
}

/**Desktop */
email {
  font-family: "Inter", sans-serif;
  font-size: 16px;
  font-style: bold;
  color: #64ffda;
  font-weight: normal;
  margin-bottom: 30px;
  position: relative;
  top: 20px;
  
}

/**Mobile */
@media screen and (min-width: 12.5em) and (max-width: 31.25em) {

  email {
    font-size: 10px;
    position: relative;
    top: -10px;
    margin-bottom: 0px;
  }
}

email:hover {
  color: #a8b2d1;
}

/**Desktop */
.copyright {
  font-family: "Inter", sans-serif;
  font-size: 16px;
  font-style: bold;
  color: #a8b2d1;
  font-weight: normal;
  margin-bottom: 30px;
  position: relative;
  top: 20px;
  bottom: 10px;
}

/**Mobile */
@media screen and (min-width: 12.5em) and (max-width: 31.25em) {

  .copyright {
    font-size: 10px;
    position: relative;
    top: -10px;
    bottom: 0px;
    margin: 0 auto;
  }
}

.copyright:hover {
  color: #64ffda;
}

</style>