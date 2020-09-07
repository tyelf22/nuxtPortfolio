<template>
  <div class="projCards">
    <div class="first hero">
      <img
        class="hero-profile-img"
        src="https://athemes.com/wp-content/uploads/Big-Slam-Basketball-WordPress-Theme.jpg"
        alt
      />
      <div class="hero-description-bk"></div>
      <div class="hero-logo">
        <img
          src="https://www.yadatov.com/wp-content/uploads/2019/12/Yadatov-Full-Logo-WhiteGold-square.png"
          style="background:black"
          alt
        />
      </div>
      <div class="hero-description">
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
      </div>
      <div class="hero-date">
        <p>20.02.2019</p>
      </div>
      <div class="hero-btn">
        <a href="#"><i class="fab fa-github fa-2x"></i></a>
      </div>
      <div class="second-btn">
        <a href="#"><i class="fas fa-link fa-2x"></i></a>
      </div>
    </div>

    <div class="first hero">
      <img
        class="hero-profile-img"
        src="https://athemes.com/wp-content/uploads/Big-Slam-Basketball-WordPress-Theme.jpg"
        alt
      />
      <div class="hero-description-bk"></div>
      <div class="hero-logo">
        <img
          src="https://www.yadatov.com/wp-content/uploads/2019/12/Yadatov-Full-Logo-WhiteGold-square.png"
          style="background:black"
          alt
        />
      </div>
      <div class="hero-description">
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
      </div>
      <div class="hero-date">
        <p>20.02.2019</p>
      </div>
      <div class="hero-btn">
        <a href="#"><i class="fab fa-github fa-2x"></i></a>
      </div>
      <div class="second-btn">
        <a href="#"><i class="fas fa-link fa-2x"></i></a>
      </div>
    </div>

        <div class="first hero">
      <img
        class="hero-profile-img"
        src="https://athemes.com/wp-content/uploads/Big-Slam-Basketball-WordPress-Theme.jpg"
        alt
      />
      <div class="hero-description-bk"></div>
      <div class="hero-logo">
        <img
          src="https://www.yadatov.com/wp-content/uploads/2019/12/Yadatov-Full-Logo-WhiteGold-square.png"
          style="background:black"
          alt
        />
      </div>
      <div class="hero-description">
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
      </div>
      <div class="hero-date">
        <p>20.02.2019</p>
      </div>
      <div class="hero-btn">
        <a href="#"><i class="fab fa-github fa-2x"></i></a>
      </div>
      <div class="second-btn">
        <a href="#"><i class="fas fa-link fa-2x"></i></a>
      </div>
    </div>

        <div class="first hero">
      <img
        class="hero-profile-img"
        src="https://athemes.com/wp-content/uploads/Big-Slam-Basketball-WordPress-Theme.jpg"
        alt
      />
      <div class="hero-description-bk"></div>
      <div class="hero-logo">
        <img
          src="https://www.yadatov.com/wp-content/uploads/2019/12/Yadatov-Full-Logo-WhiteGold-square.png"
          style="background:black"
          alt
        />
      </div>
      <div class="hero-description">
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
      </div>
      <div class="hero-date">
        <p>20.02.2019</p>
      </div>
      <div class="hero-btn">
        <a href="#"><i class="fab fa-github fa-2x"></i></a>
      </div>
      <div class="second-btn">
        <a href="#"><i class="fas fa-link fa-2x"></i></a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {};
  },
};
</script>

<style>
.projCards {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  width: 100%;
}

/* BEGIN CARD DESIGN */
.hero {
  display: inline-block;
  position: relative;
  width: 350px;
  min-width: 350px;
  height: 350px;
  border-radius: 30px;
  overflow:hidden;
  box-shadow: 5px 5px 30px rgba(0, 0, 0, 0.3);
  margin: 20px 8px;
}

.hero-profile-img {
  height: 70%;
}

.hero-description-bk {
  background-image: linear-gradient(0deg , #3f5efb, #EA178C);
  border-radius: 30px;
  position: absolute;
  top: 55%;
  left: -5px;
  height: 65%;
  width: 108%;
  transform: skew(19deg, -9deg);
}



.hero-logo {
  height: 80px;
  width: 80px;
  border-radius: 20px;
  background-color: #fff;
  position: absolute;
  bottom: 30%;
  left: 30px;
  overflow:hidden;
  box-shadow: 5px 5px 30px rgba(0, 0, 0, 0.7);
}

.hero-logo img {
  height: 100%;
}

.hero-description {
  position: absolute;
  color: #fff;
  font-weight: 900;
  left: 150px;
  bottom: 20%;
}

.hero-btn {
  position: absolute;
  color: #fff;
  right: 30px;
  bottom: 2%;

}

.second-btn {
  position: absolute;
  color: #fff;
  right: 100px;
  bottom: 2%;
}

.hero-btn a {
  color: #fff;
  text-decoration: none;
}

.second-btn a {
  color: #fff;
  text-decoration: none;
}

.hero-date {
  position: absolute;
  color: #fff;
  left: 30px;
  bottom: 10%;
}
</style>
