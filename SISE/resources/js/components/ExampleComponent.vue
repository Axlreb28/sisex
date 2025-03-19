<template>
    <div>
      <h1>{{ mensaje }}</h1>
    </div>
  </template>
  
  <script setup>
  import { ref } from 'vue';
  
  const mensaje = ref('Hola desde Vue 3 con Laravel!');
  </script>
  