<template>
  <div class="header">
    <div class="hero">
    <div class="container-fluid">
      <div class="row d-flex justify-content-center text-center">
        <div class="col-12">
          <p class="line-1">WAGMI</p>
        </div>
        <div class="col-12">
          <router-link to="/about"
      ><button class="btn btn-danger" v-show="true">
        Explore
      </button></router-link
    >
        </div>
      </div>
    </div>
  </div>
  <Footer/>
  </div>
</template>

<script>
import Footer from "./Footer.vue";
export default{
  components:{Footer}
}
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap");

.header {
  text-align: center;
  overflow-x: hidden;
  background: url("https://media1.giphy.com/media/RHIKETUlUINYvV7CAO/giphy.gif?cid=ecf05e47ugz7j9p5tm2xez7oys810vcky2jo2vr5x5u941r2&rid=giphy.gif&ct=g");
  background-size: cover;
  background-position: center;
  width:100% !important;
  background-repeat: no-repeat;
  padding:200px;
  height:100vh;
  scroll-behavior: smooth;
}
 .hero .btn-danger {
  text-transform: uppercase;
  font-size: 30px;
  font-weight: 800;
  margin-top:25px;
}
div .hero{
  margin-top:250px;
}
div .line-1 {
  font-size: 50px;
  font-weight: bolder;
  color: white;
  font-family: "Press Start 2P", cursive;
  word-spacing:1cm !important;
}

@media only screen and (max-width:850px){
  .line-1 {
  font-size: 20px;
  font-weight: bolder;
  color: white;
  font-family: "Press Start 2P", cursive;
}

div .hero{
  margin-top:300px;
  text-align:center  !important;
  margin-right:none;
  margin-left:none;
}

.header {
  text-align: center;
  overflow-x: hidden;
  background: url("https://media1.giphy.com/media/RHIKETUlUINYvV7CAO/giphy.gif?cid=ecf05e47ugz7j9p5tm2xez7oys810vcky2jo2vr5x5u941r2&rid=giphy.gif&ct=g");
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  padding:50px;
  height:100vh;
  scroll-behavior: smooth;
}
}

</style>