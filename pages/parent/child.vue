<script lang="ts" setup>

useHead({
  title: 'Child Route',
  meta: [
    {
      name: 'description',
      content: 'Child Route'
    }
  ]
})

</script>

<template>
  <div>
    <h1>I'm a child view</h1>
    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Nisi consequuntur culpa, reprehenderit odit iusto eos non impedit pariatur ullam eius obcaecati omnis. Corporis dicta saepe fugiat officiis eius veritatis quaerat.</p>
  </div>
</template>

<style scoped>

div {
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 5px;
}

</style>
