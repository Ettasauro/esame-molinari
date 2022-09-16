<!-- Please remove this file from your project -->
<template>
  <section class="section section--work col col-12">

    <div class="section-titolo col col-6 pr4">
      <h1>Le nostre piccole operaie</h1>
      <p>Greenlist is a simple Slack plugin that gives you the tools to unite your workforce in the battle against climate change and reward their greener choices with fun challenges and badges.</p>
      <a class="link link--button pt2" href="#"> Api Miellifere</a>
    </div>


     <div class="img-operaie">
       <img src="../img/operaie.jpg" alt="" class="img--operaie relative">
     </div>

</section>
  
</template>

<style>
  .section--work {
    display: flex;
    justify-content: space-between;
    height: 100vh;
    background-color: #F7B21A;
  
    }

    .section-titolo {
    color: #F7B21A;
    }


    .img-operaie {
      margin-top: 100px;
      margin-right: 100px;
      margin-left: 200px;

    }
  

    .section-titolo h1{
    font-family: 'Prata', serif;
    font-size: calc(3vw + 1.375rem);
    margin-top: 120px;
    margin-bottom: 2rem;
    padding-left: 80px;
    color: white;
    }

    .section-titolo p {
    font-family: 'Prata', serif;
    font-size: 1.125rem;
    padding-left: 80px;
    padding-right: 120px;
    margin-bottom: 80px;
    color: white;
    }

    .section--img {
    padding-left: 6rem;
    }

    .img--operaie {
      height: 500px;
      width: auto;
      margin-top: 24px;
      border-radius: 12px;
      
      }

  

    a.link--button {
    font-family: 'Raleway', sans-serif;
    font-weight: 500;
    font-size: 16px;
    border-radius: 4px;
    background-color: white;
    color:#F7B21A;
    padding: 1rem 2rem 1rem 2rem;
    opacity: 1;
    transition: opacity 0.4s ease;
    will-change: auto;
    margin-left: 80px;

    }

    a.link--button:hover {
    opacity: 0.8;

    }

    .categorie {
      display: flex;
      justify-content: space-between;
    }

</style>

<script>
export default {
  name: 'NuxtTutorial'
}
</script>
