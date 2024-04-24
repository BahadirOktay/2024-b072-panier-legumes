<script setup>
import LegumesFiche from '@/components/LegumesFiche.vue'
</script>

<template>
  <h1>Nos Légumes</h1>
  <ul>
    <li><LegumesFiche :legume="{nom: 'Poivron', prix: 5, couleur: 'Rouge'}"/></li>
  </ul>
</template>

<style scoped>
ul {
  padding-left: 0;
  margin-top: 0;
  list-style-type: none;
}
</style>
