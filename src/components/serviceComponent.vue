<template>
  <div class="bg-color p-5">
      <div class="service-part container-fluid">
        <div class="text-center">
            <h2 class="fw-blod">See Our Notch Services</h2>
            <p class="p-title">Sed ut Unde omnis unusquische faber ipse sue fortune, lorem ipusm ominibus, ancora inibus ultrum ominibus Lorem ipsum dolor sit amet consectetur adipisicing </p>
        </div>
        <div class="cards pt-5 d-flex  container-md">
            <div class="card col-3 text-center d-flex flex-column align-items-center mx-1 pt-5">
                    <font-awesome-icon class="icon-size"  icon="fa-solid fa-video"/>
                    <h3 class="fs-5 fw-bold pt-4">Work With a Team</h3>
                    <p class="px-2">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ea cumque, minima mollitia vestibulus dinamicus</p>
                    <a href="#">Read more &#62;</a>
            </div>
            <div class="card col-3 text-center d-flex flex-column align-items-center mx-1 pt-5">
                    <font-awesome-icon class="icon-size"  icon="fa-solid fa-video"/>
                    <h3 class="fs-5 fw-bold pt-4">Work With a Team</h3>
                    <p class="px-2">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ea cumque, minima mollitia vestibulus dinamicus</p>
                    <a href="#">Read more &#62;</a>
            </div>
            <div class="card col-3 text-center d-flex flex-column align-items-center mx-1 pt-5">
                    <font-awesome-icon class="icon-size"  icon="fa-solid fa-video"/>
                    <h3 class="fs-5 fw-bold pt-4">Work With a Team</h3>
                    <p class="px-2">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ea cumque, minima mollitia vestibulus dinamicus</p>
                    <a href="#">Read more &#62;</a>
            </div>
            <div class="card col-3 text-center d-flex flex-column align-items-center mx-1 pt-5">
                    <font-awesome-icon class="icon-size"  icon="fa-solid fa-video"/>
                    <h3 class="fs-5 fw-bold pt-4">Work With a Team</h3>
                    <p class="px-2">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ea cumque, minima mollitia vestibulus dinamicus</p>
                    <a href="#">Read more &#62;</a>
            </div>
        </div>     
      </div>
  </div>
</template>

<script>
export default {
name : 'serviceComponent'
}
</script>

<style scoped>
   .bg-color{
    background-color: #051642;
   }
   .icon-size{
 font-size: x-large;
 color: orange;

    }
   .service-part{
   background: url(../../public/images/pattern_background.png);
  background-repeat: no-repeat;
  background-size: cover;
  color: white;}
  .p-title{
    width: 600px;
    margin: 0 auto;
  }
  .card{
    background-color: #071b50;
    height: 300px;
  }
  a{
    color: orange;
    text-decoration: none;
  }
</style>