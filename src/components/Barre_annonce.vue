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
<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@700&display=swap" rel="stylesheet">
  </head>
  <div class="color-marron">
<p>
  offre  flash :  profitez de -25% dés 50$ d’achat *     
</p>
</div>
</template>

<style scoped>

@import url('https://fonts.googleapis.com/css2?family=Roboto&display=swap'); 

.color-marron{
  background-color:#F4D2B9;
  height:47px;
  width:100%;
  display:flex;
  flex-direction: column;
  align-items: center;
justify-content: center;

}
p{
 
    color:white;
    font-family:'Roboto', cursive;
}
</style>
