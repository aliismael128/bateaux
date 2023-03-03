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
        crossorigin="anonymous" referrerpolicy="no-referrer" />

        <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Inter&display=swap" rel="stylesheet">

    </head>
<div class="navar">
    <ul id="navar_flex">

        <li><a href="#">SERVICE  EXCLUSIFS</a></li>
        <li><a href="#">NOS ENGAGEMENT</a></li>
        <li><a href="#">OFFRES SPECIALE</a></li>
        <li><div id="color"> <a href="#"><input type="search" placeholder="   RECHERCHE " name="recherche" id="recheinput"> <i class="fa-solid fa-magnifying-glass" id="color_black"></i></a></div></li>
    </ul>
  
</div>


</template>

<style scoped>
.navar{
display:flex;
flex-direction:row;
background-color: black;
width:100%;
height:47px;

}

ul,li,a{
    text-decoration:none;
    list-style:none;
    color: white;
    font-family: 'Inter', sans-serif;
}

#navar_flex{
display:flex;
align-items:center;
justify-content:space-around;
width:100%;
}

#recheinput{

font-size:18px;
border:none;
}

#color{
 background-color:white;
 height:30px;
 width:260px;
 display:flex;
 align-items:center;
justify-content:center;
}
#color{
    
    border-radius:20px;
}

#color_black{
    color:black !important;
}

</style>
