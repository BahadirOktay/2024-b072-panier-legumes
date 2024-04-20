<script setup>

import LegumesFiche from '@/components/LegumesFiche.vue'
</script>

<template>
  <h1>Nos légumes</h1>
  <ul>
    <li><LegumesFiche :legume="{nom: 'Poivron', prix: 5, couleur: 'Rouge'}"/></li>
  </ul>
</template>

<style scoped>

</style>