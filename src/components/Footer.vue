<template>
  <div class="footer">
    <p class="copyright">Built by Isaac Hernández</p>
    <email>isaachernandezeseverino@gmail.com</email>
  </div>
</template>

<style scoped>

.footer {
  display: flex;
  box-sizing: border-box;
  justify-content: space-between;
  align-items: baseline;
  padding: 20px 0px 5px 0px;
}

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

email:hover {
  color: #a8b2d1;
}

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

.copyright:hover {
  color: #64ffda;
}

</style>