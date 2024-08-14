<script setup>
import { defineAsyncComponent } from "vue";
import navbar from "../components/navbar.vue";
// import Dmodel from './components/3dmodel.vue';
import projects from '../components/projectdisplay.vue';
const Dmodel = defineAsyncComponent(() => import("../components/3dmodel.vue"));

</script>

<template>
  <navbar />

  <main class="homemain">
    <section class="upperhome">
      <div class="modelcard">
        <Dmodel />
      </div>

      <div class="textconn">
        <div class="mainname">
          <h1>Sharyar</h1>
          <h1>Naveed</h1>
        </div>
        <div class="normaltext">
          <h5>web developer from <br />Paksitan</h5>
        </div>
      </div>
    </section>

    <section class="bottomhome">
      <div class="emailme">
        <h3>
          <a href="mailto:sharyarmalik430@gmail.com"> Contact Me</a>
        </h3>
      </div>
      <div class="scrollconn">
        <div class="arrowicon">
          <img src="../assets/right-arrow.png" alt="" />
        </div>
        <h3>SCROLL</h3>
      </div>
      <div class="icons">
        <a href="https://www.instagram.com/sharyar_naveed/">
          <svg
            width="32"
            height="32"
            viewBox="0 0 32 32"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              d="M15.9957 10.6647C13.0578 10.6647 10.6602 13.0623 10.6602 16.0002C10.6602 18.9381 13.0578 21.3357 15.9957 21.3357C18.9336 21.3357 21.3312 18.9381 21.3312 16.0002C21.3312 13.0623 18.9336 10.6647 15.9957 10.6647ZM31.9982 16.0002C31.9982 13.7907 32.0182 11.6013 31.8941 9.39585C31.7701 6.83417 31.1857 4.56067 29.3125 2.68744C27.4352 0.81021 25.1657 0.229829 22.604 0.105747C20.3946 -0.0183344 18.2052 0.00167884 15.9997 0.00167884C13.7902 0.00167884 11.6008 -0.0183344 9.39536 0.105747C6.83368 0.229829 4.56019 0.814213 2.68696 2.68744C0.809722 4.56468 0.22934 6.83417 0.105259 9.39585C-0.0188226 11.6053 0.00119056 13.7947 0.00119056 16.0002C0.00119056 18.2056 -0.0188226 20.3991 0.105259 22.6045C0.22934 25.1662 0.813725 27.4397 2.68696 29.3129C4.56419 31.1902 6.83368 31.7706 9.39536 31.8946C11.6048 32.0187 13.7943 31.9987 15.9997 31.9987C18.2092 31.9987 20.3986 32.0187 22.604 31.8946C25.1657 31.7706 27.4392 31.1862 29.3125 29.3129C31.1897 27.4357 31.7701 25.1662 31.8941 22.6045C32.0222 20.3991 31.9982 18.2096 31.9982 16.0002ZM15.9957 24.2096C11.4527 24.2096 7.78631 20.5432 7.78631 16.0002C7.78631 11.4572 11.4527 7.7908 15.9957 7.7908C20.5387 7.7908 24.2051 11.4572 24.2051 16.0002C24.2051 20.5432 20.5387 24.2096 15.9957 24.2096ZM24.5413 9.37183C23.4806 9.37183 22.6241 8.51527 22.6241 7.45458C22.6241 6.39388 23.4806 5.53732 24.5413 5.53732C25.602 5.53732 26.4586 6.39388 26.4586 7.45458C26.4589 7.70644 26.4095 7.9559 26.3133 8.18865C26.217 8.42141 26.0758 8.63289 25.8977 8.81099C25.7196 8.98909 25.5082 9.1303 25.2754 9.22654C25.0426 9.32278 24.7932 9.37215 24.5413 9.37183Z"
              fill="black"
            />
          </svg>
        </a>
        <a href="https://www.linkedin.com/in/sharyar-naveed-a3b14a27b/">
          <svg
            version="1.0"
            xmlns="http://www.w3.org/2000/svg"
            width="32"
            height="32"
            viewBox="0 0 512.000000 512.000000"
            preserveAspectRatio="xMidYMid meet"
          >
            <g
              transform="translate(0.000000,512.000000) scale(0.100000,-0.100000)"
              fill="#000000"
              stroke="none"
            >
              <path
                d="M2315 5109 c-800 -83 -1501 -518 -1927 -1196 -604 -960 -491 -2229
272 -3065 423 -463 951 -740 1585 -830 118 -17 511 -16 635 0 579 80 1097 337
1491 739 130 132 157 163 243 277 256 341 423 757 488 1211 17 118 17 512 0
630 -43 303 -122 561 -247 814 -134 268 -270 459 -483 674 -395 400 -889 649
-1457 733 -123 18 -478 26 -600 13z m-660 -1105 c71 -25 156 -111 180 -184 58
-170 -20 -349 -179 -409 -187 -70 -377 -12 -462 141 -27 49 -29 61 -29 153 0
84 4 107 22 141 47 88 116 144 212 171 59 17 190 10 256 -13z m1900 -859 c101
-28 213 -92 285 -165 77 -78 123 -153 162 -262 55 -157 58 -195 58 -859 l0
-609 -310 0 -310 0 0 548 c0 432 -3 561 -14 613 -26 122 -75 192 -164 236 -79
39 -191 40 -272 2 -72 -34 -132 -96 -172 -177 l-33 -67 -3 -577 -3 -578 -310
0 -309 0 0 940 0 940 310 0 310 0 0 -132 1 -133 25 30 c14 17 43 51 64 77 73
86 217 165 345 188 71 13 269 4 340 -15z m-1737 -957 l2 -938 -315 0 -315 0 0
933 c0 514 3 937 7 940 4 4 144 6 312 5 l306 -3 3 -937z"
              />
            </g>
          </svg>
        </a>
        <a href="https://github.com/sharyarnaveed">
          <svg
            version="1.0"
            xmlns="http://www.w3.org/2000/svg"
            width="32"
            height="32"
            viewBox="0 0 512.000000 512.000000"
            preserveAspectRatio="xMidYMid meet"
          >
            <g
              transform="translate(0.000000,512.000000) scale(0.100000,-0.100000)"
              fill="#000000"
              stroke="none"
            >
              <path
                d="M2247 4995 c-1043 -126 -1913 -881 -2167 -1880 -59 -234 -74 -356
-74 -610 -1 -129 5 -259 13 -315 108 -783 536 -1431 1212 -1841 206 -124 479
-239 570 -239 45 0 55 4 85 34 22 22 34 44 35 63 2 40 -3 448 -4 449 -1 1 -42
-5 -92 -13 -108 -17 -273 -12 -360 12 -115 30 -202 79 -279 158 -64 63 -81 90
-144 217 -83 169 -138 244 -230 308 -142 100 -165 144 -87 171 31 10 54 11
103 3 136 -22 259 -109 355 -251 120 -178 219 -247 389 -271 78 -11 185 1 285
31 71 22 71 22 98 131 18 70 67 163 111 209 l25 26 -63 7 c-103 12 -293 55
-386 88 -168 59 -276 123 -395 237 -222 212 -326 520 -314 931 4 141 9 178 31
255 36 121 88 223 164 323 48 64 60 86 53 100 -21 40 -41 168 -41 261 0 107
18 219 50 317 25 73 38 78 145 63 136 -19 330 -99 506 -209 71 -45 80 -48 111
-39 84 24 309 59 450 69 228 17 538 -10 737 -64 l54 -15 91 56 c175 108 358
183 495 203 108 15 117 10 145 -79 13 -42 29 -111 36 -154 17 -103 8 -293 -17
-372 l-19 -60 46 -56 c150 -187 212 -376 211 -645 -1 -671 -304 -1054 -930
-1179 -64 -12 -142 -26 -174 -30 l-58 -7 35 -38 c43 -48 88 -135 112 -216 15
-51 18 -122 23 -504 5 -334 9 -451 19 -467 17 -31 63 -53 108 -53 93 0 453
163 659 297 165 109 299 219 435 359 385 395 615 869 691 1424 20 144 17 507
-5 655 -172 1140 -1081 2015 -2234 2150 -154 18 -464 18 -615 0z"
              />
            </g>
          </svg>
        </a>
      </div>
    </section>
  </main>



<main class="projectconnn">
<projects/>
</main>
</template>

<style scoped>
.homemain {
  /* border: 2px solid green; */
  height: 85vh;
}
.upperhome {
  /* border: 2px solid red ; */
  width: 100%;
  height: 85%;
  display: flex;
  justify-content: space-around;
  align-items: center;
}
.modelcard {
  /* border: 2px solid greenyellow; */
  width: 40%;
  height: 88%;
}
.textconn {
  /* border: 2px solid brown; */
  display: flex;
  justify-content: center;
  width: 48%;
  flex-direction: column;
  height: 85%;
}
.mainname {
  /* border: 2px solid orangered; */
  /* flex-direction: column-reverse; */
  flex-direction: column;
  padding: 10px 10px;
  /* word-spacing: 3px; */
  height: 50%;
  display: flex;
}
.mainname h1 {
  font-size: 6rem;

  line-height: 90%;
  font-family: var(--logofont);
  font-weight: 400;
  word-break: break-all;
}
.mainname h1:nth-last-child(1) {
  margin-left: 30%;
}

.normaltext {
  /* border: 2px solid brown; */
  height: 25%;
  display: flex;
  align-items: center;
  padding: 10px 10px;
}
.normaltext h5 {
  font-size: 1.2rem;
  font-family: var(--writingfont);
  font-weight: 400;
  margin: 2px 10px;
}

.bottomhome {
  /* border: 2px solid purple; */
  height: 15%;
  display: flex;
  justify-content: space-evenly;
}
.emailme {
  /* border: 2px solid green; */
  width: 25%;
  display: flex;
  justify-content: center;
  align-items: center;
}
.emailme h3 {
  font-family: var(--writingfont);
  font-size: 1.4rem;
  text-decoration: underline;
}
.emailme h3 a {
  color: black;
}
.scrollconn {
  /* border: 2px solid brown; */
  width: 25%;
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 1%;
}
.scrollconn {
  font-family: var(--writingfont);
  font-size: 1.1rem;
}
.arrowicon {
  /* border: 2px solid brown; */
  width: 10%;
  height: 80%;
  margin: 5px 5px;
  display: flex;
  justify-content: center;
  align-items: center;
  overflow: hidden;
}
.arrowicon img {
  width: 80%;
  height: 40%;
  animation: theani 3s ease infinite;
}

@keyframes theani {
  0% {
    transform: translateY(-120%);
  }
  30% {
    transform: translateY(0);
  }
  70% {
    transform: translateY(0);
  }
  100% {
    transform: translateY(120%);
  }
}

.icons {
  /* border: 2px solid red ; */
  width: 25%;
  display: flex;
  justify-content: space-evenly;
  align-items: center;
}

.icons a {
  /* border: 2px solid purple; */
  width: 12%;
  height: 55%;
}
.icons a svg {
  height: 100%;
  width: 100%;
}


.projectconnn{
    /* border: 2px solid red; */
    flex-direction: column;
    display: flex;
    height: 100vh;
}
</style>
