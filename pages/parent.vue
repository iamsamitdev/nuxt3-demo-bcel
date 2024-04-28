<script lang="ts" setup>

useHead({
  title: 'Parent Route',
  meta: [
    {
      name: 'description',
      content: 'Parent Route'
    }
  ]
})

</script>

<template>
  <div>
    <h1>I'm a parent view</h1>
    <NuxtPage />
  </div>
</template>

<style scoped>

h1 {
  color: blue;
  background-color: yellow;
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 5px;
}

</style>
