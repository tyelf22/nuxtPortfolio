<template>
  <div class="allCards">
    <div class="card devCard">
      <i class="icon fas fa-code"></i>
      <h3>Development</h3>
      <p>I like to code things from scratch, and enjoy bringing ideas to life in the browser.</p>
      <h4>Languages I speak:</h4>
    </div>
      <div class="card desCard">
        <i class="icon fas fa-pencil-ruler"></i>
      <h3>Design</h3>
      <p>I value simple content structure, clean design patterns, and thoughtful interactions.</p>
      <h4>Things I enjoy designing:</h4>
    </div>
  </div>
</template>

<script>
import posts from '../posts'
export default {
    data() {
        return {
            posts
        }
    }
};
</script>

<style>
.allCards {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  border: 1px solid red;
  width: 100%;
}

.card{
  margin: 15px 0;
  border: 1px solid black;
  width: 100%;
  text-align: center;
}

.card .icon {
  color: #EA178C;
  font-size: 70px;
  margin: 5px 0 20px 0;
}

.card h3{
  font-weight: 700;
  font-size: 20px;
}

.card h4 {
  color: #EA178C;
}

</style>