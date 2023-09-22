<template>
  <v-container class="mainCont" fluid>
    <div class="wave one"></div>
    <div class="wave two"></div>
    <div class="wave three"></div>
    <div class="welcomeImage">
      <div class="title">
        <h1>Hello,</h1>
        <h3>
          I'm
          <span>Tyson Elfors</span> and I am a
          <span>&lt;Web Developer&gt;</span>. Feel free to take a look around, enjoy your stay.
        </h3>
      </div>
      <div class="fixedImage"></div>
    </div>
    <div class="contact-button infoBtn">
      <a href="#info"><i class="fas fa-user-alt"></i></a> 
    </div>
    <div class="contact-button projectBtn">
     <a href="#projCards"><i class="fas fa-hammer"></i></a> 
    </div>
    <div class="contact-button contactBtn">
      <a href="#form"><i class="far fa-envelope"></i></a> 
    </div>
    
    
    <div class="welcomeText" id="info">
      <div class="outsideFooter">
        <h1>Full-Stack Web Developer & Designer</h1>
        <h3>A Full-Stack Web Developer with 4+ years in web development, 2 years in software development, and a good eye for design. Excels at
            Web application development, including using the agile process with Git and modern web tools. Passionate about
            all things technology, with an unmatched willingness to continuously learn.
        </h3>
        <div class="articles">
          <Cards/>
        </div>
        <h1>Recent Work</h1>
        <h3>
          Here are a few projects I've worked on recently. Want to see more?
          <a href="mailto: tyelf22@gmail.com">
            <span>Email me.</span>
          </a>
        </h3>
        <div class="articles projCards">
          <ProjectCards id="projCards" />
        </div>
        <div class="contact">
          <ContactUs id="form" />
        </div>
      </div>
      <div class="form">
        <Footer />
      </div>
    </div>
  </v-container>
</template>

<script>
export default {
  head() {
    return {
      title: "Tyson Elfors",
    };
  },
};
</script>

<style scoped>
.mainCont {
  display: flex;
  padding: 0;
  font-family: "Martel Sans", sans-serif;
  overflow-x: hidden;
  position: relative;
}



/* Waves */
.wave {
  position: absolute;
  top: -1000px;
  right: 50%;
  left: 50%;
  transform: translate(-50%, 0);
  width: 1000px;
  height: 1025px;
  background-color: #F22F46;
  opacity: 0.6;
  border-radius: 40%;
  z-index: 99;
}
.wave.one {
  animation: wave 15s linear -1s infinite;
}
.wave.two {
  animation: wave 18s linear -1s infinite;
}
.wave.three {
  animation: wave 21s linear -1s infinite;
}
@keyframes wave {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(360deg);
  }
}

.welcomeImage {
  width: 50%;
  height: 9vh;
}

.fixedImage {
  background-color: #1e1e1e; /* Used if the image is unavailable */
  height: 500px; /* You must set a specified height */
  width: 50%;
  height: 100vh;
  position: fixed;
  top: 0;
  left: 0;
  z-index: -1;
}

.title {
  position: fixed;
  top: 20%;
  left: 20px;
  width: 45%;
  color: white;
  font-size: 30px;
}

.title h1 {
  font-size: 70px;
}

.title span {
  color: #F22F46;
}

/* Buttons */

.infoBtn {
  top: 40%;
}

.projectBtn {
  top: 50%;
}

.contactBtn {
  top: 60%;
}

.divider {
  position: fixed;
  left: 50%;
  transform: translate(-50%, 0);
  height: 10px;
  width: 30px;
  background: #F22F46;
}

.contact-button {
  position: fixed;
  left: 50%;
  transform: translate(-50%, 0);
  color: white;
  padding: 5px 5px;
  border-radius: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  
}
.contact-button{
  transition: all 0.5s ease-in-out;
  box-shadow: 0px 0px 0px 2px #F22F46;
}

.contact-button i {
  color: white;
  background: #F22F46;
  border-radius: 50px;
  padding: 10px;
  font-size: 22px;
}

.contact-button:hover {
  box-shadow: none;
  cursor: pointer;
  transform: translate(-50%, 0);
}
/* End Buttons */

.welcomeText {
  width: 50%;
  /* padding: 50px; */
  height: auto;
}

.outsideFooter{
  padding: 50px;
}

.welcomeText h1 {
  text-align: center;
  margin-top: 30px;
}

.welcomeText h3 {
  font-weight: 400;
  text-align: center;
}

.welcomeText a {
  text-decoration: none;
}

.welcomeText span {
  color: #F22F46;
}

.projCards {
  margin-bottom: 100px;
}

.articles {
  display: flex;
  justify-content: center;
}



/* Media Query */
@media only screen and (max-width: 500px) {
  .title h3 {
    font-size: 24px;
  }
}

/* Media Query */
@media only screen and (max-width: 800px) {
  .mainCont {
    display: block;
  }

  .outsideFooter{
    padding: 60px 10px 0;
  }

  /* Waves */
  .wave {
    top: -920px;
  }

  .welcomeImage {
    width: 100%;
    height: 100%;
  }

  .fixedImage {
    height: 500px;
    width: 100%;
    position: absolute;
  }

  .title {
    position: static;
    margin: 30px auto 0;
    width: 100%;
    padding: 0 50px;
  }

  .title h1 {
    font-size: 50px;
    position: relative;
  }

  .divider {
    position: absolute;
    top: 480px;
    left: 50%;
    transform: translate(-50%, 0);
    height: 40px;
    width: 10px;
    background: #F22F46;
  }


/* Buttons */
.infoBtn {
  top: 475px;
  left: 30%;
  
}

.projectBtn {
  top: 475px;
  left: 50%;
  
}

.contactBtn {
  top: 475px;
  left: 70%;
  
}

.contact-button {
  position: absolute;
  color: white;
  padding: 5px 5px;
  border-radius: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  
}
.contact-button{
  transition: all 0.5s ease-in-out;
  box-shadow: 0px 0px 0px 2px #F22F46;
}

.contact-button i {
  color: white;
  background: #F22F46;
  border-radius: 50px;
  padding: 10px;
  font-size: 22px;
}

.contact-button:hover {
  box-shadow: none;
  cursor: pointer;
  transform: translate(-50%, 0);
}

/* End Buttons */

  .welcomeText {
    width: 100%;
    margin: 0 auto;
    margin-top: 140px;
    height: auto;
  }
}
</style>

