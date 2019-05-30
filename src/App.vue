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
          <div class="navbar-nav mx-auto">
            <div class="nav-item px-lg-4">
              <router-link class="nav-link text-uppercase text-expanded" to="/">Home</router-link>
            </div>
            <div class="nav-item px-lg-4">
              <router-link class="nav-link text-uppercase text-expanded" to="/about">About</router-link>
            </div>
            <div class="nav-item px-lg-4">
              <router-link class="nav-link text-uppercase text-expanded" to="/products">Our Product</router-link>
            </div>
            <div class="nav-item px-lg-4">
              <router-link class="nav-link text-uppercase text-expanded" to="/contact">Contact Us</router-link>
            </div>
          </div>
        </div>
                  <img class="navbar-toggler" data-target="#navbarResponsive" aria-controls="navbarResponsive" aria-expanded="false" aria-label="Toggle navigation" src="../public/mobile-logo-icon.png" id="icon-toggler"/>

      </div>
    </nav>
    <router-view />
    <footer class="footer text-faded text-center py-5">
      <div class="container">
        <p class="m-0 small">Copyright &copy; RangeSavers {{new Date().getFullYear()}}</p>
      </div>
    </footer>
  </div>
</template>
