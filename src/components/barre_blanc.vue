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
   
    <div id="espace">
        <h1 class="transparent">njnn</h1>
    </div>
<div class="fle-box">
<ul id="lex_box">
<li>
    <a href="#"> <div class="algn">  <p> <img src="/src/components/icons/OAP_picto-secure.png" alt="#" class="image_1">  </p> <p class="kr">jjn</p> <p> Paiement sécurisé </p>  
    </div>
</a> 
</li> 
<li>
    <a href="#"> <div class="algn">    <p><img src="/src/components/icons\OAP_picto-48h_delivery.png" alt="#" class="image_1">  <p class="kr">jjn</p>  <p>  Livraison 48h* </p>  </p> 
    </div>
</a> 
</li> 
<li>
    <a href="#"> 
        <div class="algn"> 
            <p><img src="/src/components/icons/OAP_picto-free_samples.png" alt="#" class="image_1">   <p class="kr">jjn</p>  </p>  <p>Échantillons x1 </p>  
        </div> 
    </a>
 </li> 
<li>
    <a href="#">
         <div class="algn">
            <p><img src="/src/components\icons\OAP_picto-free_delivery.png" alt="#" class="image_1"> </p> <p class="kr">jjn</p>  <p> Livraison  offerte*</p>
         </div>
         </a>
 </li> 

</ul>
</div>
</template>

<style scoped>

#espace{
 background-color:white;
}
.transparent{
    background-color: transparent;
    color:transparent;
}


.image_1{
    height:50px;
    width:50px;
    border-radius:30px;
}
.fle-box{
    background-color:black;
    width:100%;
    height:15vh;
    display: flex;
    justify-content: center;
    align-items: center;
}
#lex_box{
  display: flex;
  width:100%;
  justify-content: space-around;
  align-items: center;

}
li,a{
   color: white; 
   font-size:20px;
   font-family: 'Inter', sans-serif;
}

.algn{
    display: flex;
    justify-content: center;
    align-items: center;
    background-color:transparent;
}

.kr{
    color:transparent;
    background-color:transparent;
}

</style>
