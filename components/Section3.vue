<!-- Please remove this file from your project -->
<template>
  <section class="section section-about">

    <div class="container-about">
      <div class="abstract-slak">
        <img src="../img/logo_about.svg" alt="" class="logo-about">
       <h1>Benvenut*</h1>
        <p>Grazie per essere passat* a trovarci, se desideri avere più informazioni sulla vita delle nostre piccole operaie, sentiti liber* di contattarci</p>
      </div>

      <div class="contatti">
        <div class="phone">
          <img src="../img/phone.svg" alt="" class="phone-svg">
          <h3 class="contatti-title">Chiamaci</h3>
          <h4 class="contatti-sub">A tua disposizione 24 ore su 24.</h4>
        </div>

        <div class="mail">
          <img src="../img/mail.svg" alt="" class="mail-svg">
          <h3 class="contatti-title">Scrivici</h3>
          <h4 class="contatti-sub">Ti vergogni di parlare? Scrivici!</h4>
        </div>

        <div class="bee">
          <img src="../img/bee.svg" alt="" class="bee-svg">
          <h3 class="contatti-title">Casa nostra</h3>
          <h4 class="contatti-sub">Vieni a scoprire le nostre arnie.</h4>
        </div>
      </div>

     
         <img class="image-bee" src="../img/bee_about_img.jpg" alt="">
     
  
    </div>
  </section>

</template>

<style>
  .section-about {
    height: 100vh;
    background-color: #F7B21A;
  }
    .logo-about {
      height: 140px;
    }
  
    .contatti-title {
      font-family: 'Prata', serif;
      font-size: 34px;
      color: white;
    }
  
    .contatti-sub {
      font-family: 'Raleway', sans-serif;
      font-weight: 400;
      font-size: 18px;
      color: white;
    }
  
    .contatti {
      display: flex;
      justify-content: space-between;
      margin-left: 200px;
      margin-right: 200px;
    }
  
   /* phone */
   .phone-svg {
      width: 100px;
      margin-top: 24px;
      margin-bottom: 14px;
    }
  
   .phone {
    border:1px solid white;
    border-radius: 12px;
    width: 300px;
    height: 240px;
    text-align: center;
    }
  
  /* mail */
  .mail-svg {
    width: 100px;
    margin-top: 24px;
    margin-bottom: 14px;
    
     }
    
    .mail {
      border:1px solid white;
      border-radius: 12px;
      width: 300px;
      height: 240px;
      text-align: center;
    }
  
    /* bee */
  .bee-svg {
    width: 100px;
    margin-top: 24px;
    margin-bottom: 14px;
    
     }
    
    .bee {
      border:1px solid white;
      border-radius: 12px;
      width: 300px;
      height: 240px;
      text-align: center;
    }
  
  
  
    .section-slak {
      background-color: #F7B21A;
      height: 110vh;
      display: inline-block;
      display: flex;
      justify-content: space-between;
      margin: none;
    }
  
    .abstract-slak {
      text-align: center;
      padding-top: 2rem;
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
  
  .image-bee {
   position: relative;
   left: 420px;
    top: 40px;
   border-radius: 20px;
  
  }
  
  
  
  
  @media (max-width: 768px) {
    .contatti {
      display: flex;
      justify-content: space-between;
      flex-direction: column;
      margin-left: 80px;
      margin-right: 80px;
      margin-bottom: 100px;
    }
  
    .container-about {
    text-align: center;
  
    }
  
    .section-about {
      height: 200vh;
    }
  
    .phone {
      margin: 24px;
    }
  
    .bee {
      margin: 24px;
    }
  
    .mail {
      margin: 24px;
    }
  
    .image-bee {
      position: relative;
      width: 80%;
      left: 0px;
      top: -4px;
     
     }
     
  
  }
  
</style>

<script>
export default {
  name: 'NuxtTutorial'
}
</script>
