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
            NFT project with a simple and fun dynamic game. Evolving/leveling up
            pixelated rats art into a full retro rat by correctly answering the
            question at each level. At the end you can burn your rat to receive 
            Aztral tokens.
          </p>
          <p class="stack-title">Technology I collaborated with:</p>
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
               Chai
              </p>
            </li>
          </ul>
          <button class="btn" @click="retroRatz">See project</button>
        </div>
      </div>
      <div class="time">
        <div class="time-content">
          <h4 class="sub-heading">Featured Project</h4>
          <h3 class="project-title">Johnny's Time</h3>
          <p class="description-box">
            NFT project with a collection of only 108 with the genetics of Johnny Deep.
            Each person has a total of 5 variants from young to old. A simple game that puts
            at the edge of the fate of the owners by running a randomized mechanism that freezes
            whoever tokens get selected.
          </p>
          <p class="stack-title">Technology I collaborated with:</p>
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
               Chai
              </p>
            </li>
            <li>
              <p>
               Vue.js
              </p>
            </li>
            <li>
              <p>
               Tailwind
              </p>
            </li>
            <li>
              <p>
               Ether.js
              </p>
            </li>
          </ul>
          <button class="btn">See project</button>
        </div>
      </div>
      <div class="aztral">
        <div class="aztral-content">
          <h4 class="sub-heading">Featured Project</h4>
          <h3 class="project-title">Aztral</h3>
          <p class="description-box">
            A development studio and collective of creator's striving to make fun and innovative
            products with technologies to transform the creator economy with innovative tools and new
            approaches to content distribution and monetization.
          </p>
          <p class="stack-title">Technology I collaborated with:</p>
          <ul class="stack">
            <li>
              <p>
               Solidity
              </p>
            </li>
          </ul>
          <button class="btn" @click="aztralNetwork">See project</button>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>

const retroRatz = () => {
  window.location.href = 'https://ratz.aztral.network/';
}

const aztralNetwork = () => {
  window.location.href = 'https://aztral.network/';
}
</script>


<style scoped>

.main-container {
  box-sizing: border-box;
}

/**Desktop */
.title {
  display: flex;
  font-family: "Inter", sans-serif;
  font-weight: bold;
  font-size: 42px;
  color: #ccd6f6;
  justify-content: flex-end;
  margin-top: 200px;
  background: linear-gradient(#a0baf7);
}

/**Mobile */
@media screen and (min-width: 12.5em) and (max-width: 31.25em) {

  .title {
    font-size: 18px;
    margin-top: 90px;
    margin-bottom: 10%;
    justify-content: center;
  }
}

/**Tablet */
@media screen and (min-width: 31.25em) and (max-width:  56.25em) {

  .title {
    font-size: 28px;
    margin-top: 200px;
    justify-content: center;
    
  }
}

/**Desktop */
.title::before {
  content: "";
  width: 40%;
  position: relative;
  bottom: 18px;
  right: 20px;
  border-bottom: 1px solid #ccd6f6;
  opacity: 0.5;
}

/**Mobile */
@media screen and (min-width: 12.5em) and (max-width: 31.25em) {

  .title::before {
   width: 0%;
  }

}

/**Tablet */
@media screen and (min-width: 31.25em) and (max-width:  56.25em) {

  .title::before {
    width: 0%;
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
    align-items: center;
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


/**Desktop */
.retro-content {
  display: flex;
  flex-direction: column;
 
}

/**Mobile */
@media screen and (min-width: 12.5em) and (max-width: 31.25em) {

  .retro-content {
    align-items: flex-start;
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
.retro-content .stack-title {
  font-family: 'Inter', sans-serif;
  font-size: 14px;
  font-weight: bold;
  color: #a8b2d1; 
}

/**Mobile */
@media screen and (min-width: 12.5em) and (max-width: 31.25em) {
  .retro-content .stack-title {
    font-size: 10px;
  }
}


/**Desktop */
.retro-content .stack {
  display: flex;
  box-sizing: border-box;
  flex-direction: row;
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


/**Desktop */
.time-content {
  display: flex;
  flex-direction: column;
}

/**Mobile */
@media screen and (min-width: 12.5em) and (max-width: 31.25em) {

  .time-content {
    align-items: flex-end;
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
.time-content .stack-title {
  font-family: 'Inter', sans-serif;
  font-size: 14px;
  font-weight: bold;
  color: #a8b2d1; 
}

/**Mobile */
@media screen and (min-width: 12.5em) and (max-width: 31.25em) {
  .time-content .stack-title {
    font-size: 10px;
  }
}

/**Desktop */
.time-content .stack {
  display: flex;
  box-sizing: border-box;
  flex-direction: row;
  position: relative;
  bottom: 5%;
  right: 8%;
}

/**Mobile */
@media screen and (min-width: 12.5em) and (max-width: 31.25em) {

  .time-content .stack {
    position: relative;
    bottom: 5%;
    left: 2%;
    
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


/**Aztral project */

/**Desktop */
.aztral {
  display: flex;
  box-sizing: border-box;
  justify-content: flex-start;
}


/**Desktop */
.aztral-content {
  display: flex;
  flex-direction: column;
}

/**Mobile */
@media screen and (min-width: 12.5em) and (max-width: 31.25em) {

  .aztral-content {
    align-items: flex-start;
  }
}


/**Desktop */
.aztral-content .sub-heading {
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

  .aztral-content .sub-heading {
    font-size: 10px;
  }
}

/**Desktop */
.aztral-content .project-title {
  font-family: "Inter", sans-serif;
  font-size: 24px;
  color: #ccd6f6;
  text-decoration: none;
  position: relative;
  bottom: -5%;
}

/**Mobile */
@media screen and (min-width: 12.5em) and (max-width: 31.25em) {

  .aztral-content .project-title {
    font-size: 16px;

  }
}

.aztral-content .project-title:hover {
  color: #64ffda;
}

/**Desktop */
.aztral-content .description-box {
  display: flex;
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

  .aztral-content .description-box {
    font-size: 10px;
    width: 300px;
    max-height: 100px;

  }
}

/**Desktop */
.aztral-content .stack-title {
  font-family: 'Inter', sans-serif;
  font-size: 14px;
  font-weight: bold;
  color: #a8b2d1; 
}

/**Mobile */
@media screen and (min-width: 12.5em) and (max-width: 31.25em) {
  .aztral-content .stack-title {
    font-size: 10px;
  }
}

/**Desktop */
.aztral-content .stack {
  display: flex;
  flex-direction: row;
  box-sizing: border-box;
  position: relative;
  bottom: 5%;
  right: 8%;
}

/**Mobile */
@media screen and (min-width: 12.5em) and (max-width: 31.25em) {

  .aztral-content .stack {
    position: relative;
    bottom: 5%;
    right: 12%;
    
  }
}

/**Desktop */
.aztral-content .stack li {
  font-family: 'Inter', sans-serif;
  list-style-type: none;  
  color: #a8b2d1; 
  font-size: 14px;
  margin-right: 10px;

}

/**Mobile */
@media screen and (min-width: 12.5em) and (max-width: 31.25em) {

  .aztral-content .stack li {
    font-size: 8px;
    margin-right: 5px;

  }
}

.aztral-content .stack li:hover {
  color: #64ffda;
}

/**Desktop */
.aztral-content .btn {
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

  .aztral-content .btn {
    font-size: 10px;
    padding: 10px;
    width: 30%;

  }
}

.btn:hover {
  color: #a8b2d1;
  border-color: #a8b2d1;

}

/**End of Aztral project*/

</style>