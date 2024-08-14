


<template>

<div class="headingpro">
   <h1>Projects</h1>
</div>

  <div class="wrapper">
        <div class="containerproject">
            <input type="radio" name="slide" id="c1" checked>
            <label for="c1" class="card">
                <div class="row">
                    <div class="icon">1</div>
                    <div class="description">
                        <h4><a href="https://github.com/sharyarnaveed/Food-Website">Food Website</a></h4>
                        <p>A visually appealing and responsive food website showcasing culinary delights.</p>
                    </div>
                </div>
            </label>


            <input type="radio" name="slide" id="c2" >
            <label for="c2" class="card">
                <div class="row">
                    <div class="icon">2</div>
                    <div class="description" >
                        <h4 ><a style="color: white;" href="https://github.com/sharyarnaveed/Car-Vista">Car Vista</a></h4>
                        <p style="color: white;">A sleek and modern car showroom website featuring an elegant display of the latest vehicles.</p>
                    </div>
                </div>
            </label>



            <input type="radio" name="slide" id="c3" >
            <label for="c3" class="card">
                <div class="row">
                    <div class="icon">3</div>
                    <div class="description">
                        <h4><a style="color: white;" href="https://github.com/sharyarnaveed/clinic">Clinic Management</a></h4>
                        <p style="color: white;">A robust clinic management system streamlining patient records, administrative tasks.</p>
                    </div>
                </div>
            </label>



            <input type="radio" name="slide" id="c4" >
            <label for="c4" class="card">
                <div class="row">
                    <div class="icon">4</div>
                    <div class="description">
                        <h4><a style="color: white;" href="https://prosensia.pk/">ProSensia</a></h4>
                        <p style="color: white;">Prosensia is a startup focused on predictive maintenance for air conditioning systems. </p>
                    </div>
                </div>
            </label>

            <input type="radio" name="slide" id="c5" >
            <label for="c5" class="card">
                <div class="row">
                    <div class="icon">5</div>
                    <div class="description">
                        <h4 style="color: white;"><a style="color: white;" href="https://github.com/sharyarnaveed/Quiz-Master">Quiz Master</a></h4>
                        <p style="color: white;">A dynamic quiz website offering interactive and engaging quizzes score tracking.</p>
                    </div>
                </div>
            </label>


        </div>
    </div>
</template>


<style scoped>


.headingpro{
    /* border: 2px solid yellow; */
height: 18%;
display: flex;
align-items: end;
padding: 5px 20px;
}
.headingpro h1
{
    font-size: 3.5rem;
    margin: 5px 20px;
    font-family: var(--writingfont);
}



.wrapper {
    width: 100%;
    height: 82%;
    display: flex;
    align-items: center;
    justify-content: center;
   
}

.containerproject {
    height: 400px;
    display: flex;
    flex-wrap: nowrap;
    justify-content: start;
}

.card {
    width: 80px;
    border-radius: .75rem;
    background-size: cover;
    cursor: none;
    overflow: hidden;
    border-radius: 2rem;
    margin: 0 10px;
    display: flex;
    align-items: flex-end;
    transition: .6s cubic-bezier(.28,-0.03,0,.99);
    box-shadow: 0px 10px 30px -5px rgba(0,0,0,0.8);
}

.card > .row {
    color: black;
    display: flex;
    flex-wrap: nowrap;

}

.card > .row > .icon {
    background: #19191a;
    color: white;
    border-radius: 50%;
    width: 50px;
    display: flex;
    justify-content: center;
    align-items: center;
    margin: 15px;
    font-size: 1.1rem;
    font-family: var(--writingfont);
}

.card > .row > .description {
    display: flex;
    justify-content: center;
    flex-direction: column;
    overflow: hidden;
    height: 80px;
    width: 520px;
    opacity: 0;
    transform: translateY(30px);
    transition-delay: .3s;
    transition: all .3s ease;
}

.description p {
    color: black;
    padding-top: 5px;
    font-size: 1.1rem;
    font-family: var(--writingfont);
}

.description h4 {
    text-transform: uppercase;
    font-size: 1.6rem;
    font-family: var(--writingfont);
}
.description h4 a
{
    color: black;
}
input {
    display: none;
}

input:checked + label {
    width: 600px;
}

input:checked + label .description {
    opacity: 1 !important;
    transform: translateY(0) !important;
}

.card[for="c1"] {
    background-image: url('https://images.unsplash.com/photo-1722891067479-5fd39edbfc3d?q=80&w=1582&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D');
}
.card[for="c2"] {
    background-position: center;
    background-image: url('https://images.unsplash.com/photo-1676136449197-babffb1125f0?q=80&w=1527&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D');
}
.card[for="c3"] {
    background-position: center;
    background-image: url('https://images.unsplash.com/photo-1701014159251-f86a81a6fe13?q=80&w=1563&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D');
}
.card[for="c4"] {
    background-position: center;
    background-image: url('https://images.unsplash.com/photo-1721041011353-298585b7c8f6?q=80&w=1527&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D');
}

.card[for="c5"] {
    background-image: url('https://images.unsplash.com/photo-1722269160081-5bce2d5fdde2?q=80&w=1632&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D');
}


</style>
