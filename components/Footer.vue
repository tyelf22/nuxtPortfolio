<template>
  <footer>
    <div class="bottom-contain">
      <section class="newsletter">
        <div class="newsletter-inner">
          <div class="container">
            <h3>Sign up for our monthly newsletter...</h3>
          </div>
        </div>
      </section>
    </div>
    <div class="bottomFoot">
        <p>code and design by: &copy;2020 Tyson Elfors</p>
    </div>
  </footer>
</template>

<script>
export default {};
</script>

<style scoped>
/* SLANTED AREA */

.bottom-contain {
  padding-top: 140px;
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
  padding: 50px 0 150px 0;
  text-align: center;
  margin: -50px -50px -150px -50px;
}

.newsletter-inner {
  margin: 0 50px;
  -webkit-transform: rotate(5.2deg);
  -moz-transform: rotate(5.2deg);
  -o-transform: rotate(5.2deg);
  -ms-transform: rotate(5.2deg);
  transform: rotate(5.2deg);
}

footer .bottomFoot{
    width: 100%;
    background: #ea178c;
    text-align: center;
    color: rgb(248, 248, 255);
}
</style>