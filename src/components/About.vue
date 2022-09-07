<template>
  <div class="about">
    <div class="container-fluid">
      <div class="row d-flex justify-content-center text-center">
        <div class="col-md-12">
          <iframe
            width="600"
            height="300"
            src="https://dsqqu7oxq6o1v.cloudfront.net/motion-array-1236428-LtZoueJcpI-high.mp4"
            title="YouTube video player"
            frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
            allowfullscreen
          ></iframe>
          
        </div>
        <div class="col-lg-6 col-md-12 text-start" id="koi">
          <p>Explore Koi</p>
        </div>
      </div>
    </div>
    <div class="container-fluid">
      <div class="row d-flex justify-content-end text-center">
        <div class="col-lg-3 col-md-6">
          <div class="card" style="width: 18rem" id="red">
            <div class="card-body">
              <h5 class="card-title">
                <img
                  src="https://jolhighfashion.com/wp-content/uploads/2022/03/awgeDVD.gif"
                  class="img-fluid"
                />
              </h5>
              <h6 class="card-subtitle mb-2">VIDOES</h6>
            </div>
          </div>
        </div>
        <div class="col-lg-3 col-md-6">
          <div class="card" style="width: 18rem" id="white">
            <div class="card-body">
              <h5 class="card-title">
                <img
                  src="https://jolhighfashion.com/wp-content/uploads/2022/03/awgeForum.gif"
                  class="img-fluid"
                />
              </h5>
              <h6 class="card-subtitle mb-2">FORUM</h6>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="container-fluid">
      <div class="row d-flex justify-content-end text-center">
        <div class="col-lg-3 col-md-6">
          <div class="card" style="width: 18rem" id="white">
            <div class="card-body">
              <h5 class="card-title">
                <img
                  src="https://jolhighfashion.com/wp-content/uploads/2022/03/Shopping_perspective_matte.png"
                  class="img-fluid"
                />
              </h5>
              <h6 class="card-subtitle mb-2">SHOP</h6>
            </div>
          </div>
        </div>

        <div class="col-lg-3 col-md-6">
          <div class="card" style="width: 18rem" id="red">
            <div class="card-body">
              <h5 class="card-title">
                <img
                  src="https://jolhighfashion.com/wp-content/uploads/2022/03/question-block-red.gif"
                  class="img-fluid"
                />
              </h5>
              <h6 class="card-subtitle mb-2">ABOUT</h6>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="container-fluid">
      <div class="row d-flex justify-content-end text-center">
        <div class="col-lg-3 col-md-6">
          <div class="card" style="width: 18rem" id="white">
            <div class="card-body">
              <h5 class="card-title">
                <img
                  src="https://jolhighfashion.com/wp-content/uploads/2022/03/pager.gif"
                  class="img-fluid"
                />
              </h5>
              <h6 class="card-subtitle mb-2">CONTACT</h6>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="container-fluid" id="marquee">
      <div class="column d-flex justify-content-center text-center">
        <div class="col-12">
          <marquee
            ><span class="koi">EXPLORE KOI</span> 
            <span class="style">CRAZY VOGUE</span>
            <span class="koi"> SUPER STYLISH</span>
            <span class="style"> FASHION STYLE</span></marquee
          >
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
div .about {
  background: #212529 !important;
  overflow-x: hidden;
  margin-top: 60px;
  color: white;
  width: 100%;
  padding: 30px;
}
@media only screen and (max-width: 900px) {
  div iframe {
    width: 350px !important;
    margin-right: none;
    margin-left: none;
  }
}
div #koi {
  font-family: "Press Start 2P", cursive;
  font-size: 30px;
  margin-top: 50px !important;
  padding: 5px;
}
.card {
  margin: 20px;
}
.card-title img {
  height: 60px;
  width: 60px;
}
.card h6 {
  font-family: "Press Start 2P", cursive;
  font-size: 20px;
  margin: 20px;
  padding: 20px;
}
div #red {
  background-color: rgb(255, 0, 0) !important;
  color: white !important;
  border: none;
}
div #red :hover {
  background: white;
  color: black !important;
}
#white {
  color: black !important;
  border: none;
}
#white:hover {
  background-color: rgb(255, 0, 0) !important;
  color: white !important;
}
#marquee {
  margin: 30px;
  padding: 20px;
  font-family: "Press Start 2P", cursive;
  font-size: 50px;
}
#marquee span{
  margin:20px;
  letter-spacing: -0.02em;
}
.koi{
  background: rgb(255, 0, 0);
  color:white;
  padding:20px;
  margin:5px;
  border-radius:60em;
}
.style{
  background:#212529;
  color:white;
  padding:20px;
  margin:5px;
  border-radius:60em;
}
</style>