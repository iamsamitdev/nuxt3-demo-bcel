<script lang="ts" setup>

const counter = ref(0)

useHead({
  title: 'Home',
  meta: [
    {
      hid: 'description',
      name: 'description',
      content: 'This is the home page'
    },
    {
      hid: 'keywords',
      name: 'keywords',
      content: 'home, lorem, ipsum'
    }
  ]
})

</script>

<template>
  <div>
    <h1>Home Page</h1>
    <button @click="counter++">Increment</button>
    <h1>{{ counter }}</h1>
    <button @click="counter--">Decrement</button>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Eveniet accusamus porro ut expedita magni dolores rem cupiditate officiis praesentium ea! Eos nobis voluptates delectus soluta ab repudiandae commodi quidem sed.</p>
  </div>
</template>

<style scoped>

div {
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 5px;
  margin-top: 15px;
}

</style>
