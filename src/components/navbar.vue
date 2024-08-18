<script setup>
import { onMounted, ref } from 'vue';

const buttoncheck=ref('light');

// const changecolor=()=>
// {
//     let element=document.body;
//     if(buttoncheck.value=='light'){
//         element.style.backgroundColor='white';
//         buttoncheck.value='dark';
//         }
//         else{
//             element.style.backgroundColor='black';
//             element.style.color='white';
//             buttoncheck.value='light';
//         }
// }
</script>


<template>
    <header>
<nav>
<div class="logo">
<h3>Sharyar</h3>
</div>
<ul class="listitems">
<li class="navoptions"><a href="#">Home</a></li>
<li class="navoptions"><a href="#about">About</a></li>
<li class="navoptions"><a href="#work">Work</a></li>
<li class="navoptions"><a href="https://github.com/sharyarnaveed">Github</a></li>
<!-- <button @click="changecolor" class="navoptions">{{ buttoncheck }}</button> -->

</ul>
</nav>



</header>
</template>

<style scoped>
header
{
    /* border: 2px solid red; */
    height: 12vh;
    position: static;
    width: 100%;
}
nav
{
    /* border: 2px solid blue; */
    height: 100%;
    display: flex;
    justify-content: space-between;
    padding: 0px 4vh;
}
.logo{
    /* border: 2px solid green; */
    width: 15%;
    display: flex;
    justify-content: center;
    align-items: center;
}
.logo h3
{
    font-family: var(--logofont);
    font-size: 2rem;
    font-weight: 500;
}

.listitems{
    /* border: 2px solid orange; */
    width: 40%;
    display: flex;
    justify-content: end;
    gap:2%;
    align-items: center;

}
.navoptions{
    /* border: 2px solid purple; */
    list-style: none;
    height: 35%;
    width: 14%;
    display: flex;
    justify-content: center;
    align-items: center;
}
.navoptions:not(:last-child)::after{
    margin-right: .3vw;
        margin-left: .5vw;
        display: flex;
        justify-content: center;
        align-items: center;
        content: "-";
        /* width: 30px ; */
/* background-color: black; */  

}

.navoptions a
{
    text-decoration: none;
    /* border: 2px solid red; */

    font-size: 1.2rem;
    color: black;
    height: 100%;
    /* width: 98%; */
    font-family: var(--writingfont);
    font-weight: 400;
    
    width: 100%;
    height: 80%;
}



</style>