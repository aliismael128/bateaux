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

<div class="moitie">
 <div class="partie_one">
    <div class="center_p">

 <p class="gras_taille">
    Suivez-nous
 </p>
 <br>
 <ul class="resaux">
    <li><a href="#"><img src="/src/components/icons/snap.png" alt="#" class="media"></a></li>
     <p id="transprent">transpa</p>
    <li><a href="#"><img src="/src/components/icons/instagram-new.png" alt="#" class="media"></a></li>
 </ul>
</div>

 </div>

 <div class="partie_duo">
    <div class="center">
  <ul class="flex-center">
    <li><a href="#">Conditions générales d'utilisation</a></li>
    <li><a href="#">Conditions générales de vente</a></li>
    <li><a href="#">Mentions légales</a></li>
  </ul>
</div>
 </div>
</div>

<div class="end">
  <p class="fin_page">© Camelia KB 2023</p>
</div>

</template>

<style scoped>
.moitie{
    display: flex;
    flex-direction: row;
    height:25vh;
    width:100%;
    background-color:white;
    justify-content: space-around;
}
.partie_one{
    background-color:white;
    width:40%;
}
.partie_duo{
    background-color:white;
    width:40%;
}
.center{
    display:flex;
    justify-content: center;
    align-items: center;
    height:25vh;
    
}
a,li{
    font-size:18px;
    font-family: 'Inter', sans-serif;
    line-height:220%;
}
.flex-center{
    display:flex;
    flex-direction: column;
    justify-content: center;
    align-items:center;
}
.gras_taille{
    font-weight: 700;
    font-size:30px;
}
.center_p{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    height: 25vh;

}
.media{
    height:50px;
    width:50px;
}
.resaux{
    display: flex;
    flex-direction: row;
}

#transprent{
    color: white;
    background-color:white;
    
}
.end{
    height:5vh;
    background-color:white;
    display: flex;
    align-items: flex-end;
}
.fin_page{
    font-size:20px;
    font-weight: 700;
    
}

</style>

