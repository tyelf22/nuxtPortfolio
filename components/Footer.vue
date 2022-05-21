<template>
  <footer>
    <div class="slanted"></div>
      <div class="socialMedia">
        <a href="https://github.com/tyelf22" target="_blank"><i id="github" class="fab fa-github fa-3x"></i></a> 
        <a href="https://www.linkedin.com/in/tysonelfors/" target="_blank"><i id="linkedin" class="fab fa-linkedin-in fa-3x"></i></a> 
        <a href="https://www.facebook.com/tyson.elfors" target="_blank"><i id="facebook" class="fab fa-facebook fa-3x"></i></a> 
        <a href="https://drive.google.com/file/d/1pk2PRH3KmACFkz54BBcZiL9KbWLK53Fy/view?usp=sharing" target="_blank"><i id="resume" class="far fa-file fa-3x"></i></a> 
      </div>
    <div class="bottomFoot">
        <p>code and design by: &copy;{{d.getFullYear()}} Tyson Elfors</p>
    </div>
  </footer>
</template>

<script>
export default {
  data: () => ({
    d: new Date(),
  }),
};
</script>

<style scoped>
footer .slanted {
  height: 350px;
  position: relative;
  z-index: -1;
  background-image: linear-gradient(-7.4deg, #F22F46 70%, white calc(70% + 2px)); 
  opacity: 0.9;
  margin-top: -300px;
}

footer .socialMedia {
  margin: 0 auto;
  text-align: center;
  background: #F22F46;
  opacity: 0.9;
  color: white;
}

footer .socialMedia i {
  margin: 0 5% 50px;
}

footer .socialMedia a {
  text-decoration: none;
  color: white;
}

footer #github:hover{
  color: #24292E;
  cursor: pointer;
  transition: 0.1s ease-in;
}
footer #linkedin:hover{
  color: #1F77B5;
  cursor: pointer;
  transition: 0.1s ease-in;
}
footer #facebook:hover{
  color: #1873EB;
  cursor: pointer;
  transition: 0.1s ease-in;
}
footer #resume:hover{
  color: black;
  cursor: pointer;
  transition: 0.1s ease-in;
}

footer .bottomFoot{
  width: 100%;
  background: #F22F46;
  text-align: center;
  color: rgb(248, 248, 255);
}

</style>