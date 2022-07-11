<template>
  <div id="">
    <div class="">
      <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <a class="navbar-brand" href="#">THEMESELECTION</a>

        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav mr-auto">
            <li class="nav-item mr-2">
             Services
            </li>
            <li class="nav-item mr-2">
             Our Projects
            </li>
            <li class="nav-item mr-2">
             Contect US
            </li>
            <li class="nav-item mr-2">
             Contect US
            </li>
          </ul>
          <form class="form-inline my-2 my-lg-0">
            <input
              class="form-control mr-sm-2"
              type="search"
              placeholder="Search"
              aria-label="Search"
            />
            <button class="btn btn-outline-success my-2 my-sm-0" type="submit">
              Search
            </button>
          </form>
        </div>
      </nav>
      <div id="carouselExampleControls" class="carousel slide" data-ride="carousel">
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img class="d-block w-100" src="logo.png" alt="First slide">
    </div>
    <div class="carousel-item">
      <img class="d-block w-100" src="logo.png" alt="Second slide">
    </div>
    <div class="carousel-item">
      <img class="d-block w-100" src="logo.png" alt="Third slide">
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
    </div>
    <div class="container">
      <div class="row">
        <div class="col-4 product">
          <div class="bg-dark">
            
          </div>
        </div>
        <div class="col-4 product">
          <div class="bg-dark ">
            
          </div>
        </div>
        <div class="col-4 product">
          <div class="bg-dark">
            
          </div>
        </div>
        <div class="col-4 product">
          <div class="bg-dark ">
            
          </div>
        </div>
        <div class="col-4 product">
          <div class="bg-dark">
            
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.product{
  
  height: 400px;
  padding:30px;
}
</style>
