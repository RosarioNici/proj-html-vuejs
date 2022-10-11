<template>
    <div>
        <introducingComponent class="bg-color-intro" />
        <serviceComponent/>
        <VetrinaComponent class="bg-color-intro"/>
    </div>
</template>

<script>
import IntroducingComponent from './introducingComponent.vue';
import ServiceComponent from './serviceComponent.vue';
import VetrinaComponent from './vetrinaComponent.vue';
export default {
    components: { IntroducingComponent, ServiceComponent, VetrinaComponent }
}
</script>

<style>
.bg-color-intro{
        background-color: #f8f8f8;
    }
</style>