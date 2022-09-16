<template>
  <div class="main" id="#main">
    <Navbar/>
    <Section1/>
    <Section2/>
    <Footer/>
  </div>
</template>

<script>
import { gsap } from "../js/gsap.min.js";
import { ScrollTrigger } from '../js/ScrollTrigger.min.js';
gsap.registerPlugin(ScrollTrigger);


import Footer from '../components/Footer.vue';
export default {
    name: "IndexPage",
    components: { Footer },

mounted: function(){
  gsap.to('.img-bg',{ 
    y:0,
    opacity:1,
    duration: 1,
    delay: 0.5,
    startAt: {y:80},
    scrollTrigger: {
      trigger: ".section--hero",
        }
      });
    
    gsap.to('.section-title',{ 
    y:0,
    opacity:1,
    duration: 1,
    delay: 0.5,
    startAt: {y:80},
    scrollTrigger: {
      trigger: ".section--hero",
        }
      });
}


}
</script>
