<template>
 <h1 class="bg-purple text-center mx-10 my-15 py-10">VERSUS</h1>

<section name="Oyuncunun HTML'i" class="mt-16 mx-14">
<p>Oyuncu</p>
<v-progress-linear
  v-model="oyuncu.can"
  height="40" 
  color="green"
></v-progress-linear>
</section>



<section name="Canavarin HTML'i" class="mt-16 mx-14">
<p>Canavarımsı</p>    
<v-progress-linear
  v-model="canavar.can"
  height="40" 
  color="green"
></v-progress-linear>
</section>


<section name="Tuşlar" class="text-center mt-7 mx-14">
    <v-btn class="bg-purple mt-1" block size="large">Saldir</v-btn>
    <v-btn class="bg-purple mt-1" block size="large">Pot Bas</v-btn>    
    <v-btn class="bg-purple mt-1" block size="large">Özel Atak Yap</v-btn>
</section>

</template>

<script setup>
import (ref) from "vue"

var oyuncu {
    can:100,
    saldiriGücü:250,
    kalkan:500,
}
var canavar {
    can:110,
    saldiriGücü:300,
    kalkan:600,
}
</script>

<style scoped>

</style>