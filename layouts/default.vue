<script lang="ts" setup>

useHead({
  title: 'Nuxt 3 - Layouts',
  meta: [
    {
      name: 'description',
      content: 'Nuxt 3 - Layouts'
    }
  ]
})

</script>

<template>
  <main>
    <div class="menu">
      <ul>
        <li>
          <NuxtLink to="/">Home</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/about">About</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/contact">Contact</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/service">Service</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/users/admin/2">User 2</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/category/1">Category 1</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/backend/dashboard/recent/2024/10/15/something">/backend/dashboard/recent/2024/10/15/something</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/parent/child">Parent/child</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/parent/sister">Parent/sister</NuxtLink>
        </li>
      </ul>
    </div>
    <div class="content">
      <slot />
    </div>
  </main>
</template>

<style scoped>

main {
  display: flex;
}

.menu {
  width: 20%;
  margin-right: 20px;
}

.menu ul {
  list-style: none;
  padding: 0;
}

.menu ul li {
  margin-bottom: 5px;
  word-wrap: break-word;
  border: 1px solid #ccc;
  padding: 10px;
  border-radius: 5px;
}

.menu ul li:hover {
  background-color: #f0f0f0;
}

.menu ul li a {
  text-decoration: none;
  color: blue;
  display: block;
}

</style>
