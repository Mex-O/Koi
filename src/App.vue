<template>
  <nav class="navbar bg-light fixed-top">
    <div class="container-fluid">
      <a class="navbar-brand" href="#"><img src="https://i.im.ge/2022/09/08/OfwQxM.WhatsApp-Image-2022-09-06-at-8-17-52-PM-removebg-preview.png" class="img-fluid" alt="logo"/></a>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="offcanvas"
        data-bs-target="#offcanvasNavbar"
        aria-controls="offcanvasNavbar"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div
        class="offcanvas offcanvas-end"
        tabindex="-1"
        id="offcanvasNavbar"
        aria-labelledby="offcanvasNavbarLabel"
      >
        <div class="offcanvas-header">
          <h5 class="offcanvas-title" id="offcanvasNavbarLabel">KOIGEM</h5>
          <button
            type="button"
            class="btn-close"
            data-bs-dismiss="offcanvas"
            aria-label="Close"
          ></button>
        </div>
        <div class="offcanvas-body">
          <ul class="navbar-nav justify-content-end flex-grow-1 pe-3">
            <li class="nav-item">
              <router-link to="/">Home</router-link>
            </li>
            <li class="nav-item">
              <router-link to="/About">About</router-link>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </nav>
  <router-view />
</template>

<script>
  export default{
}
</script>
<style>
@import url("https://fonts.googleapis.com/css2?family=Fjalla+One&display=swap");
body,html {
  margin: 0;
  font-family: "Fjalla One", sans-serif !important;
}
.navbar {
  color: white !important;
  margin-bottom:100px !important;
}
.navbar img{
  width:150px;
}
nav a {
  color: black;
  text-decoration: none;
  text-align: center;
  font-size: 20px;
}
a:hover {
  text-decoration: underline;
  color: black;
}
nav a:active {
  color: green !important;
}
</style>