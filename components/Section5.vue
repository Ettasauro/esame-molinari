<!-- Please remove this file from your project -->
<template>
  <div class="container5">
    <div class=".title-categorie">
      <p class="description-categorie">Categorie</p>
    </div>
    <div class="categorie">
      <div class="acacia">
        <img src="../img/acacia.jpg" alt="" class="acacia-svg">
        <h3 class="categorie-title">Chiamaci</h3>
        <h4 class="categorie-sub">A tua disposizione 24 ore su 24.</h4>
        <button class="acacia_button">Acacia</button>
      </div>
  
      <div class="millefiori">
        <img src="../img/millefiori.jpg" alt="" class="millefiori-svg">
        <h3 class="categorie-title">Scrivici</h3>
        <h4 class="categorie-sub">Ti vergogni di parlare? Scrivici!</h4>
        <button class="millefiori_button">Millefiori</button>
      </div>
  
      <div class="castagno">
        <img src="../img/castagno.jpg" alt="" class="castagno-svg">
        <h3 class="categorie-title">Casa nostra</h3>
        <h4 class="categorie-sub">Vieni a scoprire le nostre arnie.</h4>
        <button class="castagno_button">Castagno</button>
      </div>
    </div>
  </div>
  
</template>

<style>

  .container5 {
    height: 100vh;
  }
   
  .description-categorie  {
    font-family: 'Prata', serif;
    font-size: calc(3vw + 1.375rem);
    text-align: center;
    margin-top: 80px;
    color:#F7B21A;

  }
 
  .logo-about {
    height: 140px;
  }

  .categorie-title{
    font-family: 'Prata', serif;
    font-size: 34px;
    color: #F7B21A;
    margin-top: 34px;
  }

  .categorie-sub {
    font-family: 'Raleway', sans-serif;
    font-weight: 400;
    font-size: 18px;
    color:#F7B21A;
  }

  .categorie {
    display: flex;
    justify-content: space-between;
    padding-top: 60px;
    padding-left: 200px;
    padding-right: 200px;
    margin-bottom: 200px;
  }

 /* acacia */
 .acacia-svg {
    width: 200px;
    margin-top: 24px;
    margin-bottom: 14px;
    
  }

 .acacia {
  width: 300px;
  height: 240px;
  text-align: center;
  }

  .acacia_button {
    font-family: 'Raleway', sans-serif;
    font-weight: 500;
    font-size: 16px;
    border-radius: 4px;
    border: none;
    background-color: #F7B21A;;
    color: white;
    padding: 10px 42px 10px 42px;
    opacity: 1;
    transition: opacity 0.4s ease;
    will-change: auto;
    text-align: center;
    margin-top: 20px;
    }

    .acacia_buttonr {
    opacity: 0.8;

    }

/* millefiori */
.millefiori-svg {
  width: 200px;
  margin-top: 24px;
  margin-bottom: 14px;
   }
  
  .millefiori {
    width: 300px;
    height: 240px;
    text-align: center;
  }

  .millefiori_button {
    font-family: 'Raleway', sans-serif;
    font-weight: 500;
    font-size: 16px;
    border-radius: 4px;
    border: none;
    background-color: #F7B21A;;
    color: white;
    padding: 10px 42px 10px 42px;
    opacity: 1;
    transition: opacity 0.4s ease;
    will-change: auto;
    text-align: center;
    margin-top: 20px;
    }

    .millefiori_buttonr {
    opacity: 0.8;

    }

  /* castagno */
.castagno-svg {
  width: 200px;
  margin-top: 24px;
  margin-bottom: 14px;
  
   }
  
  .castagno {
 
    width: 300px;
    height: 240px;
    text-align: center;
  }

  .castagno_button {
    font-family: 'Raleway', sans-serif;
    font-weight: 500;
    font-size: 16px;
    border-radius: 4px;
    border: none;
    background-color: #F7B21A;;
    color: white;
    padding: 10px 42px 10px 42px;
    opacity: 1;
    transition: opacity 0.4s ease;
    will-change: auto;
    text-align: center;
    margin-top: 20px;
    }

    .castagno_buttonr {
    opacity: 0.8;

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

.image-bee img {
  border-radius: 12px;
  margin-top: 52px;
  margin-left: 250px;
  margin-right: 300px;
}


</style>

<script>
export default {
  name: 'NuxtTutorial'
}
</script>
