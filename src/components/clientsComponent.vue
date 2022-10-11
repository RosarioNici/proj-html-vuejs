<template>
  <div>
    <div class="text-center container-md  pt-5">
        <h1 class="fw-bold fs-3">What Our Client Say</h1>
        <div class="py-5">
            <img class="img-clients" src="../../public/images/testimonials-2.jpg" alt="">
            <p><em>Ability procedede ability fusion of skills, knowledge, understanding and imagination consolidadet by experience</em></p>
            <p><b>Luis Desalvo</b>, CREO TECH</p>
        </div>
        <hr class="py-5">
        <div class="d-flex justify-content-around">
            <div>
                <img class="img-partner" src="../../public/images/clients_partner_1-200x202.png" alt="">
            </div>
            <div>
                <img class="img-partner" src="../../public/images/clients_partner_2-200x202.png" alt="">
            </div>
            <div>
                <img class="img-partner" src="../../public/images/clients_partner_3-200x202.png" alt="">
            </div>
            <div>
                <img class="img-partner" src="../../public/images/clients_partner_4-200x202.png" alt="">
            </div>
            <div>
                <img class="img-partner" src="../../public/images/clients_partner_5-200x202.png" alt="">
            </div>
            <div>
                <img class="img-partner" src="../../public/images/clients_partner_6-200x202.png" alt="">
            </div>
        </div>
    </div>
  </div>
</template>

<script>
export default {
name: 'clientsComponent'
}
</script>

<style scoped>
.img-partner{
    width: 100px;
    border-radius: 50%;
}
.img-clients{
    border-radius: 50%;
}
</style>