<template>
  <div class="allCards">
    <div class="card frontCard">
      <i class="icon fas fa-code"></i>
      <h3>Front-End</h3>
      <p>I like to code things from scratch, and enjoy bringing ideas to life.</p>
      <h4>Languages I speak:</h4>
      <p>Javascript, HTML, CSS</p>
      <h4>Tools / Frameworks:</h4>
      <p>Vue.js, React, SCSS, LESS, BootStrap, Flexbox, CSS Grid, Vuex, Vuetify, Github</p>
    </div>
    <div class="card backCard">
      <i class="icon fas fa-server"></i>
      <h3>Back-End</h3>
      <p>I like solving problems, learning new languages, and using new tools.</p>
      <h4>Languages I speak:</h4>
      <p>NodeJS, Python, SQL, NoSQL, PHP, C#</p>
      <h4>Tools / Frameworks:</h4>
      <p>Express, SQL Server, MongoDB, Linux, Git, Netlify, Heroku, Bluehost, Docker, Postman</p>
    </div>
      <div class="card desCard">
        <i class="icon fas fa-pencil-ruler"></i>
      <h3>Design</h3>
      <p>I value simple content structure, clean design patterns, and thoughtful interactions.</p>
      <h4>Things I enjoy designing:</h4>
      <p>Web, Mobile, Apps, UX, UI, Logos</p>
      <h4>Tools:</h4>
      <p>Photoshop, Illustrator, InDesign, XD, Sketch, Invision, Hype</p>
    </div>
  </div>
</template>

<script>
export default {
    data() {
        return {
        }
    }
};
</script>

<style>
.allCards {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  width: 100%;
  margin-bottom: 100px;
}

.card{
  margin: 15px 0;
  width: 100%;
  text-align: center;
  padding: 1rem;
  border: 1px solid #e3e8ee;
  border-radius: 5px;
  box-shadow: 0 1px 2px rgba(50, 50, 93, 0.1);
}

.card .icon {
  color: #F22F46;
  font-size: 70px;
  margin: 5px 0 20px 0;
}

.card h3{
  font-weight: 700;
  font-size: 25px;
  margin: 10px 0;
}

.card h4 {
  color: #F22F46;
  margin-top: 20px;
}

/* Media Query */
/* @media only screen and (min-width: 1500px) {
  .card{
    width: 45%;
    margin: 20px 2%;

  }

} */

</style>