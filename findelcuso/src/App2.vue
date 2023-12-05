<script setup lang="ts">
// eslint-disable-next-line vue/multi-word-component-names
  import Header from './components2/Header/Header.vue';
  import Invitacion from './components2/Invitacion/Invitacion.vue';
</script>
<template>
  <Header/>
  <Invitacion :usuario="{ nombre: 'Lucas Fava', edad: 37}" />
</template>
<style scoped></style>