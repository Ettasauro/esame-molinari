<!-- Please remove this file from your project -->
<template>
  <section class="section section--hero col col-12">
    
    <div class="section-title col col-6 pr4">
      <h1>Lorem ipsum <br>dolor sit amet</h1>
      <p>Greenlist is a simple Slack plugin that gives you the tools to unite your workforce in the battle against climate change and reward their greener choices with fun challenges and badges.</p>
      <a class="link link--button1 pt2" href="#"> <img src="img/logo_slack.svg" alt=""> Api Miellifere</a>
    </div>


     <div class="img-bg">
       <img src="../img/ape_1.jpg" alt="" class="img--social_1 relative">
       <img src="../img/miele_2.jpg" alt="" class="img--social_2 relative">
     </div>
</section>
</template>

<style>
  .section--hero {
    display: flex;
    justify-content: space-between;
    height: 100vh;
  
    }

    .section-title {
    color: #F7B21A;
    opacity: 0;
    }


    .img-bg {
      background-image: url(../img/sketch.svg);
      background-repeat: no-repeat;
      opacity: 0;
    }
  

    .section-title h1 {
    font-family: 'Prata', serif;
    font-size: calc(3vw + 1.375rem);
    margin-top: 120px;
    margin-bottom: 2rem;
    padding-left: 80px;
    }

    .section-title p {
    font-family: 'Prata', serif;
    font-size: 1.125rem;
    padding-left: 80px;
    padding-right: 120px;
    margin-bottom: 80px;
    }

    .section--img {
    padding-left: 6rem;
    }

    .img--social_1 {
      height: 400px;
      width: auto;
      margin-top: 200px;
      border-radius: 12px;
      
      }

    .img--social_2 {
      height: 400px;
      width: auto;
      margin-right: 80px;
      margin-left: 24px;
      border-radius: 12px;
      
    }


    a.link--button1 {
    font-family: 'Raleway', sans-serif;
    font-weight: 500;
    font-size: 16px;
    border-radius: 4px;
    background-color: #F7B21A;;
    color: white;
    padding: 1rem 2rem 1rem 2rem;
    opacity: 1;
    transition: opacity 0.4s ease;
    will-change: auto;
    margin-left: 80px;

    }

    a.link--button:hover {
    opacity: 0.8;

    }
</style>

<script>
export default {
  name: 'NuxtTutorial'
}
</script>
