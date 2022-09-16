<!-- Please remove this file from your project -->
<template>
  <div class="container-footer">
    <div class="sign-up">
      <p class="descrizione">• • • • • • • • •</p>
      <h1>Sign up to today.</h1>
      <p class="descrizione">Greenlist is a simpte your workforce in the battle allenges and badges.</p>
      <a class="link link--button2" href="#"> <img src="img/logo_slack.svg" alt=""> Connect to Slack</a>
    </div>
  
  </div>
</template>

<style>
  .container-footer {
    display: flex;
    justify-content: space-between;
    height: 120vh;
    background-color:  #FAFAFA;
  
  }
    
    .sign-up {
      text-align: center;
      margin: 0 auto;
      padding-top: 400px;
      margin-bottom: 400px;
      width: 60%;
    }
    
  
  
    .sign-up h1 {
      font-family: 'Prata', serif;
      font-size: 70px;
      margin-bottom: 0px;
      color: black;
    
    }
    
    .sign-up span {
    color: var(--primary-color);
    
    }
  
  
  
  .descrizione {
    font-family: 'Raleway', sans-serif;
    font-size: 20px;
    padding-left: 120px;
    padding-right: 120px;
    margin-bottom: 80px;
    }
    
  
  
    a.link--button2 {
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
  
      }
  
      a.link--button2:hover {
      opacity: 0.8;
  
      }
  
      @media (max-width: 768px) { 
      .sign-up h1 {
          font-size: 44px;
        }
        .descrizione {
          font-size: 16px;
          padding-left: 20px;
          padding-right: 20px;
          margin-bottom: 80px;
          }
  
  
          .container-footer {
            height: 120vh;
      
          
          }
  
     
      }
    
</style>

<script>
export default {
  name: 'NuxtTutorial'
}
</script>
