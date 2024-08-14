<script setup>
import { defineAsyncComponent, onMounted } from 'vue';
onMounted(()=>
{
  const cursor = document.querySelector('.cursor');

const positionCursor = (e) => {
  const mouseY = e.clientY;
  const mouseX = e.clientX;

  cursor.style.top = `${mouseY}px`;
  cursor.style.left = `${mouseX}px`;
}

window.addEventListener('mousemove', positionCursor);
})


const home=defineAsyncComponent(()=>import('./views/home.vue'))


</script>

<template>
<div class="cursor"></div>


  <home/>

  

</template>