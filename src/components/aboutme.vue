<template>
   <div class="textarea">

    <div class="mainname">
          <h1>Sharyar</h1>
          <h1>Naveed</h1>
        </div>
<div class="aboutmepara">
    <div class="thepara">
       <p> I'm a web developer from KPK, Pakistan. I specialize developing web experiences
<br>
<br>
I work with organizations and individuals to create beautiful, responsive, and scalable web products tailored to their needs. Think we can create something great together? Let's talk over email. 
</p>

</div>
</div>

<div class="contactmeper">
    <h3>
          <a href="mailto:sharyarmalik430@gmail.com"> Email Me</a>
        </h3>
</div>

   </div>


   <div class="img">
    <img src="../assets/me.jpg" alt="">
   </div>
</template>

<style scoped>

.textarea
{
    /* border: 2px solid red; */
    width: 50%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    gap: 5%;
    padding: 10px 10px;
    align-items: center;
}
.img{
    /* border: 2px solid blue; */
    width: 50%;
    display: flex;
    justify-content: center;
    align-items: center;
}
.img img
{
    /* border: 2px solid red; */
    height: 80%;
    width: 90%;
}
.mainname{
    /* border: 2px solid green; */
    width: 100%;
    height: 30%;
    display: flex;
    flex-direction: column;
    justify-content: end;
}
.mainname h1 {
  font-size: 6rem;

  line-height: 90%;
  font-family: var(--headingfont);
  font-weight: 400;
  word-break: break-all;
}
.mainname h1:nth-last-child(1) {
  margin-left: 30%;
}

.aboutmepara{
    /* border: 2px solid red; */
    /* border: 2px solid green; */
    width: 100%;
    height: 30%;
    display: flex;
    flex-direction: column;
   
}

.aboutmepara::before
{
    content: "";
    /* position: absolute;/ */
    height: 4px;
    width: 10vw;
   
    background-color: black;
}

.thepara{
    /* border: 2px solid blue; */
    padding: 10px 5px;
    height: 100%;
    display: flex;
    justify-content: center;
}
.thepara p
{
    /* border: 2px solid brown; */
    width: 56%;
    font-family: var(--writingfont);
    font-size:1.1rem ;
}
.contactmeper{
    /* border: 2px solid orange; */
    width: 100%;
    height: 10%;
    display: flex;
    justify-content: center;
    align-items: start;
}
.contactmeper h3
{
    color: black;
    font-size: 1.5rem;
    font-family: var(--writingfont);
}

.contactmeper h3 a
{
    color: black;
}
</style>