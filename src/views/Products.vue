<template>
  <section class="page-section">
    <div class="container">
      <div class="card mx-auto">
        <div class="card-body">
          <h5 class="card-title">Covid 19 Disclaimer</h5>
          <p class="card-text">Due to Covid 19, we have taken the year to perfect our product. The following are photos of our previous models.</p>
        </div>
      </div>
      <br>
      <div id="carouselExampleControls" class="carousel slide" data-ride="carousel">
        <ol class="carousel-indicators">
          <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
          <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
          <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
          <li data-target="#carouselExampleIndicators" data-slide-to="3"></li>
        </ol>
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img class="d-block w-100" src="~@/assets/images/Resized_20210624_201532.jpeg" alt="First slide">
          </div>
          <div class="carousel-item">
            <img class="d-block w-100" src="~@/assets/images/Resized952021062495201623.jpg" alt="Second slide">
          </div>
          <div class="carousel-item">
            <img class="d-block w-100" src="~@/assets/images/Resized_20200804_202619_97994044766314.jpeg" alt="Third slide">
          </div>
          <div class="carousel-item">
            <img class="d-block w-100" src="~@/assets/images/Resized_20210624_201606.jpeg" alt="Fourth slide">
          </div>
        </div>
        <a class="carousel-control-prev" href="#carouselExampleControls" role="button" data-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="sr-only">Previous</span>
        </a>
        <a class="carousel-control-next" href="#carouselExampleControls" role="button" data-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="sr-only">Next</span>
        </a>
      </div>
      <br>
    </div>
  </section>
</template>

<style>
  .card {
    width: 35rem;
  }

  img {
    max-width: 50%;
    height: auto%;
    display: block;
    margin-left: auto;
    margin-right: auto;
  }
</style>
