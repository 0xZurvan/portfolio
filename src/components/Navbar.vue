<template>
    <nav class="navbar">
        <ul class="nav-list">
            <li>
              <p>
                <a href="https://twitter.com/IsaacHernndezS2">Twitter</a>
              </p>
            </li>
            <li>
              <p>
                <a href="https://github.com/IsaacHS5">GitHub</a>
              </p>
            </li>
            <li>
              <p>
                <a href="https://discord.com/users/823992612028940319/">Discord</a>
              </p>
            </li>
        </ul>
    </nav>
</template>



<style scoped>

* {
  box-sizing: border-box;
}

.navbar {
  display: flex;
  margin-top: 30px;
  justify-content: flex-start;
}


/**Desktop */
li {
  display: inline-flex;
  margin-left: 25px;
  padding-left: 25px;
  flex-direction: row;
  position: relative;
  left: 10%;
}

/** Mobile */
@media screen and (min-width: 12.5em) and (max-width: 31.25em) {
  
  li {
    display: flex;
    flex-direction: column;
    margin-left: 5px;
    padding-left: 5px;
    position: relative;
    left: 2%;
  }

}

/** Tablet */
@media screen and (min-width: 12.5em) and (max-width: 31.25em) {
  
  li {
    display: inline-flex;
    margin-left: 15px;
    scroll-padding-left: 15px;
    flex-shrink: 3;
    position: relative;
    left: 4%;
  }

}


/**Desktop */
.nav-list a {
  font-family: 'Inter', sans-serif;
  text-decoration: none;
  color: #a8b2d1; 
  font-size: 18px;
 
}

/**Mobile */
@media screen and (min-width: 12.5em) and (max-width: 31.25em) {

  .nav-list a  {
    font-size: 10px;
    position: relative;
    right: 30px;
  }
}

/**Tablet */
@media screen and (min-width: 31.25em) and (max-width:  56.25em) {

 .nav-list a  {
    font-size: 14px;
    font-size: 10px;
    position: relative;
    right: 30px;
  }
}

.nav-list a:hover {  
  color: #64ffda; 
  text-decoration: underline;
  text-decoration-style: solid;
  text-decoration-thickness: 4px;
  
}


</style>