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
  justify-content: space-between;
  align-items: baseline;
  padding: 20px 0px 5px 0px;
}

/**Mobile */
@media screen and (min-width: 12.5em) and (max-width: 31.25em) {

  .footer {
    flex-direction: column;
    justify-content: center;
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
  right: 5%;
  top: 20px;
  
}

/**Mobile */
@media screen and (min-width: 12.5em) and (max-width: 31.25em) {

  email {
    position: relative;
    left: 11%;
    top: 20px;
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
  left: 4%;
  top: 20px;
  bottom: 18px;
}

/**Mobile */
@media screen and (min-width: 12.5em) and (max-width: 31.25em) {

  .copyright {
    position: relative;
    left: 22%;
    top: 20px;
  }
}

.copyright:hover {
  color: #64ffda;
}

</style>