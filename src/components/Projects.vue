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

.main-container {
  box-sizing: border-box;
}

/**Desktop */
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

/**Mobile */
@media screen and (min-width: 12.5em) and (max-width: 31.25em) {

  .title {
    font-size: 20px;
    padding-right: 10px;
    margin-top: 150px;
    margin-bottom: 15%;
    padding-bottom: 20px;
  }
}

/**Tablet */
@media screen and (min-width: 31.25em) and (max-width:  56.25em) {

  .title {
    font-size: 34px;
    padding-right: 15px;
  }
}

/**Desktop */
.title::before {
  content: "";
  width: 30%;
  position: relative;
  bottom: 18px;
  right: 20px;
  border-bottom: 1px solid #ccd6f6;
  opacity: 0.5;
}

@media screen and (min-width: 12.5em) and (max-width: 31.25em) {

  .title::before {
    bottom: 12px;
  }

}

/**Desktop */
.projects-container {
  box-sizing: border-box;
  display: flex;
  flex-direction: column;
}

/**Mobile */
@media screen and (min-width: 12.5em) and (max-width: 31.25em) {

  .projects-container {
    justify-content: center;
  }
}

/**Tablet */
@media screen and (min-width: 31.25em) and (max-width:  56.25em) {

  .projects-container{
    justify-content: center;
  }
}

/** Retro Ratz project */

/**Desktop */
.retro-ratz {
  display: flex;
  box-sizing: border-box;
  justify-content: flex-start;
}

/**Mobile */
@media screen and (min-width: 12.5em) and (max-width: 31.25em) {

  .retro-ratz {
    justify-content: center;
  }
}

/**Tablet */
@media screen and (min-width: 31.25em) and (max-width:  56.25em) {

  .retro-ratz {
    justify-content: center;
    margin: 0px 90px 0px 10px;
  }
}

/**Desktop */
.retro-content {
  display: flex;
  flex-direction: column;
  position: relative;
  left: 8%;
}

/**Mobile */
@media screen and (min-width: 12.5em) and (max-width: 31.25em) {

  .retro-content {
    justify-content: center;
    padding: 0px 80px 0px 20px;
  }
}


/**Desktop */
.retro-content .sub-heading {
  font-family: "Inter", sans-serif;
  font-size: 15px;
  font-weight: normal;
  font-style: bold;
  color: #64ffda;
  position: relative;
  top: 12%;

}

/**Mobile */
@media screen and (min-width: 12.5em) and (max-width: 31.25em) {

  .retro-content .sub-heading {
    font-size: 10px;
  }
}


/**Desktop */
.retro-content .project-title {
  font-family: "Inter", sans-serif;
  font-size: 24px;
  color: #ccd6f6;
  text-decoration: none;
  position: relative;
  bottom: -5%;
}

/**Mobile */
@media screen and (min-width: 12.5em) and (max-width: 31.25em) {

  .retro-content .project-title {
    font-size: 16px;

  }
}


.retro-content .project-title:hover {
  color: #64ffda;
}

/**Desktop */
.retro-content .description-box {
  display: inline-flex;
  box-sizing: border-box;
  font-family: "Inter", sans-serif;
  font-size: 16px;
  width: 500px;
  max-height: 200px;
  color: #a8b2d1;
  font-weight: normal;
  border: 1px solid #112240;
  background-color: #112240;
  padding: 5%;
  box-shadow: 0px 3px 0px #64ffda;
  border-radius: 2px;

}

/**Mobile */
@media screen and (min-width: 12.5em) and (max-width: 31.25em) {

  .retro-content .description-box {
    font-size: 10px;
    width: 300px;
    max-height: 100px;

  }
}

/**Desktop */
.retro-content .stack {
  display: inline-flex;
  box-sizing: border-box;
  flex-wrap: wrap;
  position: relative;
  bottom: 5%;
  right: 8%;
}

/**Mobile */
@media screen and (min-width: 12.5em) and (max-width: 31.25em) {

  .retro-content .stack {
    position: relative;
    bottom: 5%;
    right: 12%;
    
  }
}

/**Desktop */
.retro-content .stack li {
  font-family: 'Inter', sans-serif;
  list-style-type: none;  
  color: #a8b2d1; 
  font-size: 14px;
  margin-right: 10px;

}

/**Mobile */
@media screen and (min-width: 12.5em) and (max-width: 31.25em) {

  .retro-content .stack li {
    font-size: 8px;
    margin-right: 5px;

  }
}


.retro-content .stack li:hover {
  color: #64ffda;
}

/**Desktop */
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

/**Mobile */
@media screen and (min-width: 12.5em) and (max-width: 31.25em) {

  .retro-content .btn {
    font-size: 10px;
    padding: 10px;
    width: 30%;

  }
}


.btn:hover {
  color: #a8b2d1;
  border-color: #a8b2d1;

}

/**End of Retro Ratz */


/**Time Project */

/**Desktop */
.time {
  display: flex;
  box-sizing: border-box;
  justify-content: flex-end;
}

/**Mobile */
@media screen and (min-width: 12.5em) and (max-width: 31.25em) {

  .time {
    justify-content: center;
  }
}

/**Tablet */
@media screen and (min-width: 31.25em) and (max-width:  56.25em) {

  .time {
    justify-content: center;
    margin: 0px 0px 0px 140px;
  }
}

/**Desktop */
.time-content {
  display: flex;
  flex-direction: column;
  position: relative;
  right: 10%;
}

/**Mobile */
@media screen and (min-width: 12.5em) and (max-width: 31.25em) {

  .time-content {
    justify-content: center;
    padding: 0px 20px 0px 80px;
    right: 8%;
  }
}

/**Desktop */
.time-content .sub-heading {
  font-family: "Inter", sans-serif;
  font-size: 15px;
  font-weight: normal;
  font-style: bold;
  color: #64ffda;
  position: relative;
  top: 12%;

}

/**Mobile */
@media screen and (min-width: 12.5em) and (max-width: 31.25em) {

  .time-content .sub-heading {
    font-size: 10px;
  }
}

/**Desktop */
.time-content .project-title {
  font-family: "Inter", sans-serif;
  font-size: 24px;
  color: #ccd6f6;
  text-decoration: none;
  position: relative;
  bottom: -5%;
}

/**Mobile */
@media screen and (min-width: 12.5em) and (max-width: 31.25em) {

  .time-content .project-title {
    font-size: 16px;

  }
}

.time-content .project-title:hover {
  color: #64ffda;
}

/**Desktop */
.time-content .description-box {
  display: inline-flex;
  box-sizing: border-box;
  font-family: "Inter", sans-serif;
  font-size: 16px;
  width: 500px;
  max-height: 200px;
  color: #a8b2d1;
  font-weight: normal;
  border: 1px solid #112240;
  background-color: #112240;
  padding: 5%;
  box-shadow: 0px 3px 0px #64ffda;
  border-radius: 2px;

}

/**Mobile */
@media screen and (min-width: 12.5em) and (max-width: 31.25em) {

  .time-content .description-box {
    font-size: 10px;
    width: 300px;
    max-height: 100px;

  }
}

/**Desktop */
.time-content .stack {
  display: inline-flex;
  box-sizing: border-box;
  flex-wrap: wrap;
  position: relative;
  bottom: 5%;
  right: 8%;
}

/**Mobile */
@media screen and (min-width: 12.5em) and (max-width: 31.25em) {

  .time-content .stack {
    position: relative;
    bottom: 5%;
    right: 12%;
    
  }
}

/**Desktop */
.time-content .stack li {
  font-family: 'Inter', sans-serif;
  list-style-type: none;  
  color: #a8b2d1; 
  font-size: 14px;
  margin-right: 10px;

}

/**Mobile */
@media screen and (min-width: 12.5em) and (max-width: 31.25em) {

  .time-content .stack li {
    font-size: 8px;
    margin-right: 5px;

  }
}

.time-content .stack li:hover {
  color: #64ffda;
}

/**Desktop */
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

/**Mobile */
@media screen and (min-width: 12.5em) and (max-width: 31.25em) {

  .time-content .btn {
    font-size: 10px;
    padding: 10px;
    width: 30%;

  }
}

.time-content .btn:hover {
  color: #a8b2d1;
  border-color: #a8b2d1;

}

/**End of Time Project */


/**Music project */

/**Desktop */
.astral-music {
  display: flex;
  box-sizing: border-box;
  justify-content: flex-start;
}

/**Mobile */
@media screen and (min-width: 12.5em) and (max-width: 31.25em) {

  .astral-music {
    justify-content: center;
  }
}

/**Tablet */
@media screen and (min-width: 31.25em) and (max-width:  56.25em) {

  .astral-music {
    justify-content: center;
    margin: 0px 90px 0px 10px;
  }
}

/**Desktop */
.astral-content {
  display: flex;
  flex-direction: column;
  justify-content: flex-end;
  position: relative;
  left: 8%;
}

/**Mobile */
@media screen and (min-width: 12.5em) and (max-width: 31.25em) {

  .astral-content {
    justify-content: center;
    padding: 0px 80px 0px 20px;
  }
}


/**Desktop */
.astral-content .sub-heading {
  font-family: "Inter", sans-serif;
  font-size: 15px;
  font-weight: normal;
  font-style: bold;
  color: #64ffda;
  position: relative;
  top: 12%;

}

/**Mobile */
@media screen and (min-width: 12.5em) and (max-width: 31.25em) {

  .astral-content .sub-heading {
    font-size: 10px;
  }
}

/**Desktop */
.astral-content .project-title {
  font-family: "Inter", sans-serif;
  font-size: 24px;
  color: #ccd6f6;
  text-decoration: none;
  position: relative;
  bottom: -5%;
}

/**Mobile */
@media screen and (min-width: 12.5em) and (max-width: 31.25em) {

  .astral-content .project-title {
    font-size: 16px;

  }
}

.astral-content .project-title:hover {
  color: #64ffda;
}

/**Desktop */
.astral-content .description-box {
  display: inline-flex;
  box-sizing: border-box;
  font-family: "Inter", sans-serif;
  font-size: 16px;
  width: 500px;
  max-height: 200px;
  color: #a8b2d1;
  font-weight: normal;
  border: 1px solid #112240;
  background-color: #112240;
  padding: 5%;
  box-shadow: 0px 3px 0px #64ffda;
  border-radius: 2px;

}

/**Mobile */
@media screen and (min-width: 12.5em) and (max-width: 31.25em) {

  .astral-content .description-box {
    font-size: 10px;
    width: 300px;
    max-height: 100px;

  }
}

/**Desktop */
.astral-content .stack {
  display: inline-flex;
  box-sizing: border-box;
  flex-wrap: wrap;
  position: relative;
  bottom: 5%;
  right: 8%;
}

/**Mobile */
@media screen and (min-width: 12.5em) and (max-width: 31.25em) {

  .astral-content .stack {
    position: relative;
    bottom: 5%;
    right: 12%;
    
  }
}

/**Desktop */
.astral-content .stack li {
  font-family: 'Inter', sans-serif;
  list-style-type: none;  
  color: #a8b2d1; 
  font-size: 14px;
  margin-right: 10px;

}

/**Mobile */
@media screen and (min-width: 12.5em) and (max-width: 31.25em) {

  .astral-content .stack li {
    font-size: 8px;
    margin-right: 5px;

  }
}

.astral-content .stack li:hover {
  color: #64ffda;
}

/**Desktop */
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

/**Mobile */
@media screen and (min-width: 12.5em) and (max-width: 31.25em) {

  .astral-content .btn {
    font-size: 10px;
    padding: 10px;
    width: 30%;

  }
}

.btn:hover {
  color: #a8b2d1;
  border-color: #a8b2d1;

}

/**End of Music Project*/

</style>