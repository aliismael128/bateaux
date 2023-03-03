<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>

<div id="icon_imag">
    <ul class="flex_box">
        <li><a href="#"><img src="/src/components/icons/yeux.png" alt="#"> <br> <p class="center"> Yeux</p></a></li>
        <li><a href="#"><img src="/src/components/icons/visage.png" alt="#"> <br> <p class="center"> Visage </p> </a></li>
        <li><a href="#"><img src="/src/components/icons/Crème.png" alt="#"> <br><p class="center"> Créme</p> </a></li>
        <li><a href="#"><img src="/src/components/icons/Bijoux.png" alt="#"> <br> <p class="center"> Bijoux </p> </a></li>
    </ul>
</div>


</template>

<style scoped>
 img{
    height:201px;
    width:247px;
 }


#icon_imag{
  height:67vh;
  width:100%;
  background-color:white;
  display:flex;
align-items:center;
justify-content:space-around;
  
}
.flex_box{
width:100%;
display:flex;
align-items:center;
justify-content:space-around;
/* padding-top:55px; */
}
ul,li,a{
    text-decoration:none;
    list-style:none;
    font-size:15px;
color:black;
}
.center{
  background-color:white;
  display: flex;
  align-items:center;
justify-content:center;
  width:247px;
  padding-top:10px;
}

</style>
