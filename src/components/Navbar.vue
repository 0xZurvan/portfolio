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
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@300&display=swap');

.navbar {
  display: flex;
  margin-top: 30px;
  justify-content: flex-end;
}

li {
  display: inline-flex;
  margin-right: 25px;
  padding-right: 25px;
  flex-direction: row;
  position: relative;
  right: 10%;
}

.nav-list a {
  font-family: 'Inter', sans-serif;
  text-decoration: none;
  color: #a8b2d1; 
  font-size: 18px;
 
}

.nav-list a:hover {  
  color: #64ffda; 
  
}


</style>