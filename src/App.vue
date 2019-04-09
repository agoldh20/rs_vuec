<template>
  <div id="app">
    <h1 class="site-heading text-center text-white d-none d-lg-block">
      <img src="../public/rs_logo_header.png" />
    </h1>
    <nav class="navbar navbar-expand-lg navbar-dark py-lg-4" id="mainNav">
      <div class="container">
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarResponsive" aria-controls="navbarResponsive" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarResponsive">
          <ul class="navbar-nav mx-auto">
            <li class="nav-item px-lg-4 home-selected">
              <a class="nav-link text-uppercase text-expanded" href="/">Home</a>
            </li>
            <li class="nav-item px-lg-4 about-selected">
              <a class="nav-link text-uppercase text-expanded" href="/about">About</a>
            </li>
            <li class="nav-item px-lg-4 products-selected">
              <a class="nav-link text-uppercase text-expanded" href="/products">Our Product</a>
            </li>
            <li class="nav-item px-lg-4 contact-selected">
              <a class="nav-link text-uppercase text-expanded" href="/contact">Contact Us</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <router-view />
    <footer class="footer text-faded text-center py-5">
      <div class="container">
        <p class="m-0 small">Copyright &copy; RangeSavers 2017</p>
      </div>
    </footer>
  </div>
</template>

<style></style>
