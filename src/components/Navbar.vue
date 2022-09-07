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

/**Desktop */
.navbar {
  display: flex;
  margin-top: 30px;
  justify-content: flex-end;
}

/** Mobile */
@media screen and (min-width: 12.5em) and (max-width: 31.25em) {
  .navbar {
    display: flex;
    margin-top: 30px;
    justify-content: center;
  }
}

/** Tablet */
@media screen and (min-width: 31.25em) and (max-width: 56.25em) {
  .navbar {
    display: flex;
    margin-top: 30px;
    justify-content: center;
  }
}

/**Desktop */
li {
  display: inline-flex;
  margin-right: 20px;
  flex-direction: row;

}

/** Mobile */
@media screen and (min-width: 12.5em) and (max-width: 31.25em) {
  li {
    display: inline-flex;
    flex-direction: row;
    justify-content: center;
  }
}

/** Tablet */
@media screen and (min-width: 31.25em) and (max-width: 56.25em) {
  li {
    display: inline-flex;
    margin-right: 15px;
    position: relative;
    right: 4%;
  }
}

/**Desktop */
.nav-list a {
  font-family: "Inter", sans-serif;
  text-decoration: none;
  color: #a8b2d1;
  font-size: 20px;
}

/**Mobile */
@media screen and (min-width: 12.5em) and (max-width: 31.25em) {
  .nav-list a {
    font-size: 12px;
  }
}

/**Tablet */
@media screen and (min-width: 31.25em) and (max-width: 56.25em) {
  .nav-list a {
    font-size: 16px;
  }
}

.nav-list a:hover {
  color: #64ffda;
  text-decoration: underline;
  text-decoration-style: solid;
  text-decoration-thickness: 4px;
}
</style>