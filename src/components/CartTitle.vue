<template>

    <h1>{{username}}</h1>
    
</template>

<script setup>
defineProps(['username'])
</script>

<style scoped>
h1 {
  padding: 20px;
  max-width: 1200px;
  margin: auto;
}
</style>