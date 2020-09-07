<template>
  <footer>
    <!-- <div class="bottom-contain">
      <section class="newsletter">
        <div class="newsletter-inner">
          <div class="container">
            <h3>Sign up for our monthly newsletter...</h3>
          </div>
        </div>
      </section>
    </div> -->
    <div class="slanted"></div>
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

/* SLANTED AREA */

/* .bottom-contain {
  padding-top: 300px;
  overflow: hidden;
}

.newsletter {
  -webkit-transform: rotate(-5.2deg);
  -moz-transform: rotate(-5.2deg);
  -o-transform: rotate(-5.2deg);
  -ms-transform: rotate(-5.2deg);
  transform: rotate(-5.2deg);
  background:#ea178c;
  opacity: .8;
  color: rgb(248, 248, 255);
  padding: 250px 0 150px 0;
  text-align: center;
  margin: -250px -50px -150px -50px;
}

.newsletter-inner {
  margin: 0 50px;
  -webkit-transform: rotate(5.2deg);
  -moz-transform: rotate(5.2deg);
  -o-transform: rotate(5.2deg);
  -ms-transform: rotate(5.2deg);
  transform: rotate(5.2deg);
} */

footer .slanted {
  height: 350px;
  position: relative;
  z-index: -1;
  background-image: linear-gradient(-7.4deg, #ea178c 70%, white calc(70% + 2px)); 
  opacity: 0.75;
  margin-top: -300px;
}

footer .bottomFoot{
    width: 100%;
    background: #ea178c;
    text-align: center;
    color: rgb(248, 248, 255);
}
</style>