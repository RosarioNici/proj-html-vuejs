<template>
  <div>
    <div class="text-center  py-4">
        <h1 class="fw-bold fs-3">Our Works</h1>
        <div class="container-h6">
            <h6 class="fs-6"> Illo sint iure at sapiente  odit voluptatibus, libero accusamus  doloribus!</h6>
        </div>
        <div>
            <div v-for="pic in pics" :key="pic" >
                <img :src="addPics(pic)" alt="">
                
            </div>
        </div>
    </div>
  </div>
</template>

<script>

export default {
name: 'vetrinaComponent',
data(){
    return { pics:5 }

    },
    methods: {
    addPics(number){
        return `../../public/images/case-study-gallery-${number}-1-400x300.jpg`
    }
    }
}


</script>

<style>

</style>