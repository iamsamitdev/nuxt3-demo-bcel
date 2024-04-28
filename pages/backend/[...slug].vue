<script lang="ts" setup>

useHead({
  title: 'Backend Route',
  meta: [
    {
      name: 'description',
      content: 'Backend Route'
    }
  ]
})

const route = useRoute()
console.log(route.params.slug)
const slug = ref(route.params.slug)

</script>

<template>
  <div>
    <h1>Backend Route</h1>
    <h2 v-if="$route.params.slug">Slug ({{ slug.length }})</h2>
    <ul>
      <li v-for="item in slug" :key="item">{{ item }}</li>
    </ul>
  </div>
</template>

<style scoped>

div {
  min-width: 70vw;
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 5px;
  margin-top: 15px;
}

</style>
