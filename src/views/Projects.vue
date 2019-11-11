<template>
  <div class="Projects">
    <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
      <ol class="carousel-indicators">
        <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
        <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
        <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
        <li data-target="#carouselExampleIndicators" data-slide-to="3"></li>
        <li data-target="#carouselExampleIndicators" data-slide-to="4"></li>
        <li data-target="#carouselExampleIndicators" data-slide-to="5"></li>
        <li data-target="#carouselExampleIndicators" data-slide-to="6"></li>
        <li data-target="#carouselExampleIndicators" data-slide-to="7"></li>
      </ol>
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img class="d-block w-50" src="../assets/logo.png" alt="First slide" />
          <div class="carousel-caption d-md-block">
            <h5 style="color:black;">Ebay</h5>
            <p style="color: black;">Test</p>
          </div>
        </div>
        <div class="carousel-item">
          <img class="d-block w-50" src="../assets/logo.png" alt="Second slide" />
          <div class="carousel-caption d-md-block">
            <h5 style="color:black;">Disney</h5>
            <p style="color: black;">Test</p>
          </div>
        </div>
        <div class="carousel-item">
          <img class="d-block w-50" src="../assets/logo.png" alt="Third slide" />
          <div class="carousel-caption d-md-block">
            <h5 style="color:black;">Vuex Todo</h5>
            <p style="color: black;">Test</p>
          </div>
        </div>
        <div class="carousel-item">
          <img class="d-block w-50" src="../assets/logo.png" alt="Fouth slide" />
          <div class="carousel-caption d-md-block">
            <h5 style="color:black;">Vue State Todo</h5>
            <p style="color: black;">Test</p>
          </div>
        </div>
        <div class="carousel-item">
          <img class="d-block w-50" src="../assets/logo.png" alt="Fifth slide" />
          <div class="carousel-caption d-md-block">
            <h5 style="color: black;">React Todo</h5>
            <p style="color: black;">Test</p>
          </div>
        </div>
        <div class="carousel-item">
          <img class="d-block w-50" src="../assets/logo.png" alt="Sixth slide" />
          <div class="carousel-caption d-md-block">
            <h5 style="color: black;">Tripper</h5>
            <p style="color: black;">Test</p>
          </div>
        </div>
        <div class="carousel-item">
          <img class="d-block w-50" src="../assets/logo.png" alt="Seventh slide" />
          <div class="carousel-caption d-md-block">
            <h5 style="color: black;">Cost-Go!</h5>
            <p style="color: black;">Test</p>
          </div>
        </div>
      </div>
      <a
        class="carousel-control-prev"
        href="#carouselExampleIndicators"
        role="button"
        data-slide="prev"
      >
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="sr-only">Previous</span>
      </a>
      <a
        class="carousel-control-next"
        href="#carouselExampleIndicators"
        role="button"
        data-slide="next"
      >
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="sr-only">Next</span>
      </a>
    </div>
  </div>
</template>

<style scoped>
/* h1#projects {
  text-align: center;
} */
/* p.col-sm-4 {
  text-align: center;
} */
</style>

<script>
export default {
  name: "projects",
  data: function() {
    return {};
  },
  created: function() {},
  methods: {}
};
</script>