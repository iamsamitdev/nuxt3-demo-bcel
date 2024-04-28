<script lang="ts" setup>

useHead({
  title: 'About',
  meta: [
    {
      hid: 'description',
      name: 'description',
      content: 'This is the about page'
    },
    {
      hid: 'keywords',
      name: 'keywords',
      content: 'about, lorem, ipsum'
    }
  ]
})

</script>

<template>
  <div>
    <h1>About Page</h1>
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
