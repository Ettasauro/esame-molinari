<!-- Please remove this file from your project -->
<template>
  <section class="section section-slak">

    <div class="container">
      <div class="abstract-slak">
        <h1>Prodotto nel rispetto delle piccole operaie</h1>
        <p>Whether it’s choosing reusable food and liquid containers or picking the vegetarian option for the office lunch, Greenlist allows anyone in your team to set a positive role model and influence other staff in being more cautious about plastic pollution and using resources sustainably.</p>
      </div>
  
      <div class="image-abstract">
          <img src="../img/slack.png" alt="">
      </div>
    </div>
  </section>
</template>

<style>
  .section-slak {
    background-color: #F7B21A;
    height: 100vh;
    display: inline-block;
    margin-top: 100;
    display: flex;
    justify-content: space-between;



  }

.abstract-slak {
text-align: center;
margin: 0 auto;
padding-top: 6rem;
padding-bottom: 2rem;
width: 60%;

}


.abstract-slak h1 {
font-family:  'Prata', serif;
font-size: 60px;
line-height: 1.2;
margin-top: 1rem;
margin-bottom: 2rem;
margin-left: 0px;
margin-right: 0px;
color: white;
}

.abstract-slak p {
font-family: 'Raleway', sans-serif;
font-weight: 500;
font-size: 1.125rem;
margin-bottom: 3.5rem;
color: white;
text-align: center;
padding-left: 120;
padding-right: 120;
}

.image-abstract img {
  border-radius: 12px;
}

.image-abstract {
border-radius: 12px;
position: relative;
left: 120px;


}
</style>

<script>
export default {
  name: 'NuxtTutorial'
}
</script>
