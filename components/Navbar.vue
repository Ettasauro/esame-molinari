<!-- Please remove this file from your project -->
<template>
  <div class="header--main">
    <a href="index.html"> <NuxtLink to="/"> <img class="logo" src="../img/Miellifera_logo.png" alt=""> </NuxtLink> </a> <!-- messo in a xke così clicchi e porta sempre alla home -->
    <ul class="main--menu list-reset m0">
     <li class="menu--item"> <NuxtLink to="/"> Home </NuxtLink></li>
     <li class="menu--item"> <a href="index.html">Prodotti</a> </li>
     <li class="menu--item"> <NuxtLink to="/work">Miele</NuxtLink></li>
     <li class="menu--item"> <a href=""> <NuxtLink to="/about"> About</NuxtLink></a></li>
    </ul>
</div>
</template>

<style>
  .header--main {
    display: flex;
    justify-content: space-between;
    align-items: baseline;
    background-color: #FAFAFA;
    }

    .header--main .container {
    padding-bottom: 2.5rem;
    }

    .logo {
    width: 24%;
    margin-left: 60px;
    margin-top: 18px;
    margin-bottom: 18px;

    }
    .main--menu {
    display: flex;
    flex-direction: row;
    margin-left: 2.5rem;
    }

    .menu--item {
      list-style: none;
    }

    .main--menu .menu--item a {
    color: #F7B21A;
    font-family: 'Prata', serif;
    font-weight: 800;
    position: relative;
    margin-right: 60px;
    margin-top: 22px;
    margin-bottom: 18px;
    transition: 0.3 ease;
    will-change: auto;
    opacity: 1;
    text-decoration: none;
    }

    .main--menu .menu--item a:hover {
    opacity: 0.8;
    }

    @media (max-width: 768px) {
      .logo {
        width: 120px;
        margin-left: 12px;
    
        }
        .main--menu .menu--item a {
          margin-right: 12px;
          font-size: 16px;
          }
    
    }
</style>

<script>
export default {
  name: 'NuxtTutorial'
}
</script>
