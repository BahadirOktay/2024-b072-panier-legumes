<script setup>
defineProps({
  legume: {
    type: Object,
    required: true
  }
})
</script>

<template>
  <div>
    <h2> {{legume.nom}} </h2>
    <div> {{legume.prix}} CHF </div>
    <div> {{legume.couleur}} </div>
  </div>
</template>

<style scoped>
p {
  color: red;
}
</style>
