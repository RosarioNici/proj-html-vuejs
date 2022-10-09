<template>
  <div class="bg-img-header">

        <div class="container-md d-flex justify-content-between">
            <div class="logo">
            <img src="../../public/images/logo_seo_1x.png" alt="Logo AdvanceSEO">
            </div>
            <nav class="d-flex">
                <div class="d-flex">
                    <ul class="d-flex">
                        <li><a href="#">Home</a></li>
                        <li><a href="#">Who we are</a></li>
                        <li><a href="#">What we do</a></li>
                        <li><a href="#">Where we work</a></li>
                        <li><a href="">Careers</a><button>APPLY</button></li>
                        <li><a href="#">New</a></li>
                    </ul>
                    <button>GET IN TOUCH NOW</button>
                </div>
            </nav>
        </div>

        <div class="container-md">
            <h1>SEM Campaigns Made</h1>
            <h1>Simple with AVADA</h1>
            <p>
                Lorem ipsum dolor sit amet, consectetur adipisicing elit. 
            <br>
                Recusandae quam numquam 
                necessitatibus nulla
            </p>
            <button>Buy Avada Now</button> <button>Contact US</button>
        </div>

  </div>
</template>

<script>    







export default {
    name: 'headerComponent',
   
}
</script>

<style scoped>
.bg-img-header{
  background: url(../../public/images/1-hero-image.png);
  background-repeat: no-repeat;
  background-size: cover;
}
li{
    list-style-type: none;
}
</style>