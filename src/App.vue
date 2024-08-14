<script setup>
import { defineAsyncComponent } from 'vue';



const home=defineAsyncComponent(()=>import('./views/home.vue'))


</script>

<template>

  <home/>

  

</template>