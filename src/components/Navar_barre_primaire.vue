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
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.3.0/css/all.min.css"
     integrity="sha512-SzlrxWUlpfuzQ+pcUCosxcglQRNAq/DZjVsC0lE40xsADsfeQoEypE+enwcOiGjk/bSuGGKHEyjSoQ1zVisanQ==" 
     crossorigin="anonymous" 
     referrerpolicy="no-referrer" />

     <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Yantramanav&display=swap" rel="stylesheet">
    </head>

    
<div class="navar_barre_primaire">
    <ul>
     <li><a href="#">Besoin d'aide ?</a></li>
    <li><a href="#"><p><img src="/src/components/icons/kml.png" alt="s#" id="image_1"> </p></a> </li> 
     <li><a href="#">Inscription newsletter</a></li>
     <li><a href="#">Mon compte</a></li>
     <li><a href="#">Mes favoris  <i class="fa-regular fa-heart"></i></a></li>
     

    </ul>
</div>
</template>

<style scoped>





.navar_barre_primaire{
 display: flex;
 flex-direction: row;
 height:113px;
 width:100%;
 background-color: white;
}

ul{
    width:100%;
    display:flex;
    align-items:center;
justify-content:space-around;

}
ul,li,a{
    font-family: 'Yantramanav', sans-serif;
    text-decoration:none;
    list-style:none;
    color: black;
    font-size: 16px;
}

#image_1{
    width:350px;
    height:237px;
}



</style>