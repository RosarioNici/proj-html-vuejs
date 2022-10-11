<template>
  <div class="container-md text-center d-flex flex-column justify-content-center">
        <div><img src="../../public/images/logo_seo_2x.png" alt=""></div>
            <div >
                <div class="container-fluid d-flex justify-content-center">
                    <ul class="d-flex justify-content-between">
                        <li><a href="#">Home</a></li>
                        <li><a href="#">Who we are</a></li>
                        <li><a href="#">What we do</a></li>
                        <li><a href="#">Where we work</a></li>
                        <li><a href="">Careers</a></li>
                        <li><a href="#">New</a></li>
                    </ul>
                    
                </div>
            </div>
            <div class="social"></div>
  </div>
</template>

<script>
export default {
name: 'footerComponent'
}
</script>

<style scoped>
li{
    list-style-type: none;
    margin-left: 3px;
    margin-right: 3px;
}
a{
    text-decoration: none;
    color:rgb(54, 54, 54);
}
</style>