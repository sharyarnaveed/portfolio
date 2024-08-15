<script setup>
import { onMounted } from 'vue';


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
    justify-content: space-around;
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
    justify-content: space-evenly;
    align-items: center;

}
.navoptions{
    /* border: 2px solid purple; */
    list-style: none;
    height: 50%;
    width: 12%;
    display: flex;
    justify-content: center;
    align-items: center;
}

.navoptions a
{
    /* text-decoration: none; */
    font-size: 1.3rem;
    color: black;
    font-family: var(--writingfont);
    font-weight: 400;
    width: 100%;
    height: 80%;
}



</style>