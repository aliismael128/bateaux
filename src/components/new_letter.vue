<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
    <head>

        <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Inter&display=swap" rel="stylesheet">

    </head>
   
    <div class="new_golbal">
<div class="new_letter">
 <div class="droite">
    <div class="pading_contenu">
    <h1 class="color_black">LA NEWSLETTER</h1>
    <br>
    <p>
         Recevez avant tout le monde dans votre boîte mail les dernières nouveautés <br>
           camelia KB et nos offres exclusives !
    </p>
    <br>
    <br>
    <p>
        Inscrivez vous vite et profitez de votre offre de bienvenue
    </p>
    <br>
    <br>
    <p>
        5€ offerts dès 25€ d’achats*
    </p>
    <br>
    <br>
    <form action="#" method="post#">
     <p>
        (*) Champ Obligatoire
    </p>
        <br>
        <p>
            <label for="email"> Votre e-mail</label> <br>
            <input type="email" id="email_new"> <hr>
        </p>
        <br>
        <div class="ok_petit">
      <p class="petit_taille">
        Je déclare être âgé(e) de 16 ans ou plus et souhaite recevoir des offres personnalisées <br>
 de camlia KB, mes données pouvant être utilisées à des fins statistiques et analytiques. <br>
 Vous pouvez retirer votre consentement à tout moment via le lien de désinscription présent
 dans
 notre newsletter. <br>
Pour en savoir plus, consultez notre Politique de protection des données personnelles. <br>
Camlelia KB est une marque de CAMELIA KB SA.*
</p>
<p class="checkbox"><input type="checkbox" id="scales" name="ok" checked></p>
     
    </div>
      <br>
    <button type="submit">
         <P id="color_white">  ENVOYER </P> 
         </button>
    </form>
</div>
</div>


 <div class="gauche">
    <div class="img_image">
        <p class="MAX_w">
            rango
            <!-- <img src="src\components\icons\FEMME.png" alt="#" id="taille_image"> -->
        </p>
    </div>
</div>
</div>
 </div>
</template>

<style scoped>
.new_golbal{
    width:100%;
    height:120vh;
    background-color:white;
    display:flex;
    justify-content: center;
    align-items:center;
    font-family: 'Inter', sans-serif;
}
.new_letter{
    display:flex;
    height:40vh;
   width: 90%;
    background-color:white;
    /* padding-top:10vh; */
}
.droite{
    width:70%;
    height:50vh;
    background-color:white;
    display:flex;
    justify-content:center;
    align-items: center;
}
.gauche{
    width:30% !important;
    height:50vh;
background-color:white; 
display: flex;
justify-content: center;
align-items: center;
}
.color_black{
    color: black;
    font-size:35px;
}
p{
    font-size:20px;
    color:black;
}
#email_new{
  width:100%;
  height:20px;
  background-color:transparent;
  border:none;
}

.img_image{
  height:80vh;
   width:100%;
   /* background-color:red; */
   background-image: url(../src/components/icons/FEMME.png);
   background-repeat: no-repeat;
   background-position:center;
   /* background-attachment: fixed; */
}
button{
    height:57px;
    width:153px;
    border-radius:30px;
    background-color: black;
}
#color_white{
    color:white;
}
.MAX_w{
    color:white;
    background-color:white;
}
.petit_taille{
font-size:15px;
}

.ok_petit{
    display: flex;
    flex-direction:row-reverse;
    background-color: white;
    width:100%;
    height:auto;
    line-height:26px;
}
#scales{
    height:30px;
    width:40px;
    background-color:transparent;
}

#scales[checkbox]{
    width:100%;
height:20px;
background-color:transparent;
border:none;
}
.checkbox{
    height:30px;
    background-color:white;
    /* border:2px solid black; */
    margin-right: 10px;
}
</style>
