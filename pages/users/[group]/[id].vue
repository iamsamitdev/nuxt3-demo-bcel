<script lang="ts" setup>

  // เรียกใช้ route จาก vue-router
  const route = useRoute()

  console.log(route.params.group)
  console.log(route.params.id)

</script>

<template>
  <div>
    <p>Group: {{ $route.params.group }}</p>
    <p>User ID: {{ $route.params.id }}</p>
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
