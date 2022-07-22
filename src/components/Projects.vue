<template>
  <div class="main-container">
    <div class="section-title">
      <h2 class="title">Some Things I’ve Built</h2>
    </div>
    <div class="projects-container">
      <div class="retro-ratz">
        <div class="retro-content">
          <h4 class="sub-heading">Featured Project</h4>
          <h3 class="project-title">Retro Ratz</h3>
          <p class="description-box">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce nunc
            nunc,mattis non aliquet et viverra eu risus.Etiam sed feugiat libero, id
            suscipit mi.Sed sit amet cursus ante, nec sodales lorem. Sed sit amet cursus
          </p>
          <ul class="stack">
            <li>
              <p>
               Solidity
              </p>
            </li>
            <li>
              <p>
               ERC20
              </p>
            </li>
            <li>
              <p>
               ERC721
              </p>
            </li>
            <li>
              <p>
               Hardhat
              </p>
            </li>
            <li>
              <p>
               JavaScript
              </p>
            </li>
          </ul>
          <button class="btn">See project</button>
        </div>
      </div>
      <div class="time">
        <div class="time-content">
          <h4 class="sub-heading">Featured Project</h4>
          <h3 class="project-title">Time Travelers</h3>
          <p class="description-box">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce nunc
            nunc,mattis non aliquet et viverra eu risus.Etiam sed feugiat libero, id
            suscipit mi.Sed sit amet cursus ante, nec sodales lorem. Sed sit amet cursus
          </p>
          <ul class="stack">
            <li>
              <p>
               Solidity
              </p>
            </li>
            <li>
              <p>
               ERC20
              </p>
            </li>
            <li>
              <p>
               ERC721
              </p>
            </li>
            <li>
              <p>
               Hardhat
              </p>
            </li>
            <li>
              <p>
               JavaScript
              </p>
            </li>
          </ul>
          <button class="btn">See project</button>
        </div>
      </div>
      <div class="astral-music">
        <div class="astral-content">
          <h4 class="sub-heading">Featured Project</h4>
          <h3 class="project-title">Astral Music</h3>
          <p class="description-box">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce nunc
            nunc,mattis non aliquet et viverra eu risus.Etiam sed feugiat libero, id
            suscipit mi.Sed sit amet cursus ante, nec sodales lorem. Sed sit amet cursus
          </p>
          <ul class="stack">
            <li>
              <p>
               Solidity
              </p>
            </li>
            <li>
              <p>
               ERC1155
              </p>
            </li>
            <li>
              <p>
               ERC20
              </p>
            </li>
             <li>
              <p>
               ERC721
              </p>
            </li>
            <li>
              <p>
               Hardhat
              </p>
            </li>
            <li>
              <p>
               JavaScript
              </p>
            </li>
          </ul>
          <button class="btn">See project</button>
        </div>
      </div>
    </div>
  </div>
</template>



<style scoped>
/**Title */
@import url("https://fonts.googleapis.com/css2?family=Inter:wght@800&display=swap");

/**Project names */
@import url("https://fonts.googleapis.com/css2?family=Inter:wght@100&display=swap");

/**Text */
@import url("https://fonts.googleapis.com/css2?family=Inter:wght@300&display=swap");

.main-container {
  box-sizing: border-box;
}

.title {
  display: flex;
  font-family: "Inter", sans-serif;
  font-weight: bold;
  font-size: 32px;
  color: #ccd6f6;
  justify-content: flex-end;
  position: relative;
  right: 10%;
  margin-top: 230px;
  background: linear-gradient(#a0baf7);
}

.title::before {
  content: "";
  width: 30%;
  position: relative;
  bottom: 18px;
  right: 20px;
  border-bottom: 1px solid #ccd6f6;
  opacity: 0.5;
}

.projects-container {
  box-sizing: border-box;
  display: flex;
  flex-direction: column;
}

/** Retro Ratz project */
.retro-ratz {
  display: flex;
  box-sizing: border-box;
  justify-content: flex-start;
}

.retro-content {
  display: flex;
  flex-direction: column;
  position: relative;
  left: 8%;
}

.retro-content .sub-heading {
  font-family: "Inter", sans-serif;
  font-size: 15px;
  font-weight: normal;
  font-style: bold;
  color: #64ffda;
  position: relative;
  top: 12%;

}

.retro-content .project-title {
  font-family: "Inter", sans-serif;
  font-size: 24px;
  color: #ccd6f6;
  text-decoration: none;
  position: relative;
  bottom: -5%;
}

.retro-content .project-title:hover {
  color: #64ffda;
}

.retro-content .description-box {
  display: inline-flex;
  box-sizing: border-box;
  font-family: "Inter", sans-serif;
  font-size: 16px;
  max-width: 500px;
  max-height: 500px;
  color: #a8b2d1;
  font-weight: normal;
  border: 1px solid #112240;
  background-color: #112240;
  padding: 5%;
  box-shadow: 0px 3px 0px #64ffda;
  border-radius: 2px;

}

.retro-content .stack {
  display: inline-flex;
  box-sizing: border-box;
  flex-wrap: wrap;
  position: relative;
  bottom: 5%;
  right: 8%;
}

.retro-content .stack li {
  font-family: 'Inter', sans-serif;
  list-style-type: none;  
  color: #a8b2d1; 
  font-size: 14px;
  margin-right: 10px;

}

.retro-content .stack li:hover {
  color: #64ffda;
}

.retro-content .btn {
  font-family: 'Inter', sans-serif;
  background-color: #112240;
  color: #64ffda;
  border-color: #64ffda;
  width: 30%;
  padding: 15px;
  position: relative;
  bottom: 5%;
  border-radius: 5px;
}

.btn:hover {
  color: #a8b2d1;
  border-color: #a8b2d1;

}

/**End of Retro Ratz */

/**Time Project */

.time {
  display: flex;
  box-sizing: border-box;
  justify-content: flex-end;
}

.time-content {
  display: flex;
  flex-direction: column;
  position: relative;
  right: 10%;
}

.time-content .sub-heading {
  font-family: "Inter", sans-serif;
  font-size: 15px;
  font-weight: normal;
  font-style: bold;
  color: #64ffda;
  position: relative;
  top: 12%;

}

.time-content .project-title {
  font-family: "Inter", sans-serif;
  font-size: 24px;
  color: #ccd6f6;
  text-decoration: none;
  position: relative;
  bottom: -5%;
}

.time-content .project-title:hover {
  color: #64ffda;
}

.time-content .description-box {
  display: inline-flex;
  box-sizing: border-box;
  font-family: "Inter", sans-serif;
  font-size: 16px;
  max-width: 500px;
  max-height: 500px;
  color: #a8b2d1;
  font-weight: normal;
  border: 1px solid #112240;
  background-color: #112240;
  padding: 5%;
  box-shadow: 0px 3px 0px #64ffda;
  border-radius: 2px;

}

.time-content .stack {
  display: inline-flex;
  box-sizing: border-box;
  flex-wrap: wrap;
  position: relative;
  bottom: 5%;
  right: 8%;
}

.time-content .stack li {
  font-family: 'Inter', sans-serif;
  list-style-type: none;  
  color: #a8b2d1; 
  font-size: 14px;
  margin-right: 10px;

}

.time-content .stack li:hover {
  color: #64ffda;
}

.time-content .btn {
  font-family: 'Inter', sans-serif;
  background-color: #112240;
  color: #64ffda;
  border-color: #64ffda;
  width: 30%;
  padding: 15px;
  position: relative;
  bottom: 5%;
  border-radius: 5px;
}

.time-content .btn:hover {
  color: #a8b2d1;
  border-color: #a8b2d1;

}

/**End of Time Project */

/**Music project */

.astral-music {
  display: flex;
  box-sizing: border-box;
  justify-content: flex-start;
}

.astral-content {
  display: flex;
  flex-direction: column;
  justify-content: flex-end;
  position: relative;
  left: 8%;
}

.astral-content .sub-heading {
  font-family: "Inter", sans-serif;
  font-size: 15px;
  font-weight: normal;
  font-style: bold;
  color: #64ffda;
  position: relative;
  top: 12%;

}

.astral-content .project-title {
  font-family: "Inter", sans-serif;
  font-size: 24px;
  color: #ccd6f6;
  text-decoration: none;
  position: relative;
  bottom: -5%;
}

.astral-content .project-title:hover {
  color: #64ffda;
}

.astral-content .description-box {
  display: inline-flex;
  box-sizing: border-box;
  font-family: "Inter", sans-serif;
  font-size: 16px;
  max-width: 500px;
  max-height: 500px;
  color: #a8b2d1;
  font-weight: normal;
  border: 1px solid #112240;
  background-color: #112240;
  padding: 5%;
  box-shadow: 0px 3px 0px #64ffda;
  border-radius: 2px;

}

.astral-content .stack {
  display: inline-flex;
  box-sizing: border-box;
  flex-wrap: wrap;
  position: relative;
  bottom: 5%;
  right: 8%;
}

.astral-content .stack li {
  font-family: 'Inter', sans-serif;
  list-style-type: none;  
  color: #a8b2d1; 
  font-size: 14px;
  margin-right: 10px;

}

.astral-content .stack li:hover {
  color: #64ffda;
}

.astral-content .btn {
  font-family: 'Inter', sans-serif;
  background-color: #112240;
  color: #64ffda;
  border-color: #64ffda;
  width: 30%;
  padding: 15px;
  position: relative;
  bottom: 5%;
  border-radius: 5px;
}

.btn:hover {
  color: #a8b2d1;
  border-color: #a8b2d1;

}

/**End of Music Project*/

</style>