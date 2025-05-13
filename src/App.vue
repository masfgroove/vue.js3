<!-- SCRIPT -->
<script setup>
  //Variaveis
  let nome = 'Alice';
  let idade = 25;
  let numero1 = 10;
  let numero2 = 2;
</script>

<!-- HTML -->
<template>
  <p>{{ ' Ola '  + nome + ' você tem ' + idade + 'anos.' }}</p>
  <p>{{  numero1+numero2 }}</p>
</template>