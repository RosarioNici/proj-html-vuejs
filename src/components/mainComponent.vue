<template>
    <div>
        <introducingComponent class="bg-color-intro" />
        <serviceComponent/>
        <VetrinaComponent class="bg-color-intro"/>
        <newsComponent class="bg-color-intro"/>
        <clients-component/>
        <calltoactionComponent/>
    </div>
</template>

<script>
import calltoactionComponent from './calltoactionComponent.vue';
import ClientsComponent from './clientsComponent.vue';
import IntroducingComponent from './introducingComponent.vue';
import newsComponent from './newsComponent.vue';
import ServiceComponent from './serviceComponent.vue';
import VetrinaComponent from './vetrinaComponent.vue';
export default {
    components: { IntroducingComponent, ServiceComponent, VetrinaComponent, newsComponent, ClientsComponent, calltoactionComponent }
}
</script>

<style>
        
.b,
        CalltoactionComponentg-color-intro{
        background-color: #f8f8f8;
    }
</style>