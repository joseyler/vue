<script setup lang="ts">
  defineProps<{
    usuario:any,
  }>();
</script>
<template>
  <div class="d-flex flex-column align-items-center">
    <h2>Solicitar Invitacion</h2>
    <div class="d-flex flex-row flex-wrap w-50 bg-light p-4 mx-2">
      <label class="w-50 mb-2" >Nombre</label>
      <label class="w-50 mb-2">{{ usuario.nombre }}</label>
      <label class="w-50 mb-2" >Edad</label>
      <label class="w-50 mb-2">{{ usuario.edad }}</label>
      <label class="w-50 mb-2" >Nota que se saco</label>
      <label class="w-50 mb-2">
        <input type="number" />
      </label>
    </div>
    <button class="btn btn-info">
      Quiero Ir!!
    </button>
  </div>
</template>