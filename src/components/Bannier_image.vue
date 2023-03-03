<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
<div id="bannier_image">
    <a href="#"><img id="img_1" src="/src/components/icons/WEBK.png" alt="#"></a>
</div>
</template>

<style scoped>
 #bannier_image{
    width:100%;
    height:70vh !important
;
 }
 #img_1{
width:100%;
height:70vh !important
 }


</style>