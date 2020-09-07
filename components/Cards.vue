<template>
  <div class="allCards">
    <div class="card frontCard">
      <i class="icon fas fa-code"></i>
      <h3>Front-End</h3>
      <p>I like to code things from scratch, and enjoy bringing ideas to life in the browser.</p>
      <h4>Languages I speak:</h4>
      <p>HTML, Pug, Slim, CSS, Sass, Less</p>
      <h4>Tools:</h4>
      <p>Balsamiq Mockups, Figma, Invision, Marvel, XD, Sketch, Webflow, Zeplin</p>
    </div>
    <div class="card backCard">
      <i class="icon fas fa-server"></i>
      <h3>Back-End</h3>
      <p>I like to code things from scratch, and enjoy bringing ideas to life in the browser.</p>
      <h4>Languages I speak:</h4>
      <p>NodeJS, Python, SQL, PHP</p>
      <h4>Tools:</h4>
      <p>Balsamiq Mockups, Figma, Invision, Marvel, XD, Sketch, Webflow, Zeplin</p>
    </div>
      <div class="card desCard">
        <i class="icon fas fa-pencil-ruler"></i>
      <h3>Design</h3>
      <p>I value simple content structure, clean design patterns, and thoughtful interactions.</p>
      <h4>Things I enjoy designing:</h4>
      <p>UX, UI, Web, Mobile, Apps, Logos</p>
      <h4>Tools:</h4>
      <p>Balsamiq Mockups, Figma, Invision, Marvel, XD, Sketch, Webflow, Zeplin</p>
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
  border-radius: 30px;
  box-shadow: 2px 5px 10px rgba(0, 0, 0, 0.3);
}

.card .icon {
  color: #EA178C;
  font-size: 70px;
  margin: 5px 0 20px 0;
}

.card h3{
  font-weight: 700;
  font-size: 25px;
  margin: 10px 0;
}

.card h4 {
  color: #EA178C;
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