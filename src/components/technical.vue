<script setup>
// import { onMounted } from 'vue';

defineProps({
    theexpert: String,
    logoimg:String,
    theotherlogo:String
})




</script>


<template>
    <div class="theexper">
<h5>{{ theexpert }}</h5>

<div class="logosconn">
   
   <img :src="logoimg" >
   <img v-if="theotherlogo" :src="theotherlogo" >
    <!-- <h2>{{ logo }}</h2> -->
   
</div>
    </div>


</template>

<style>

.theexper{
 border-bottom: 2px solid rgba(0, 0, 0, 0.5);
    padding: 8px 10px;
    display: flex;
    height: 20%;
    justify-content: space-between;
align-items: center;
}
.theexper h5{
    font-size: 1rem;
  font-family: var(--writingfont);
  

}
.logosconn{
/* border: 2px solid blue; */
width: 30%;
height: 98%;
display: flex;
justify-content: space-between;
align-items: center;
}

.logosconn img
{
    width: 80%;
    height: 80%;
}
</style>