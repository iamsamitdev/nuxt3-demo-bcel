<script setup lang="ts">

useHead({
    title: 'Contact',
    meta: [
        {
            hid: 'description',
            name: 'description',
            content: 'This is the contact page'
        },
        {
            hid: 'keywords',
            name: 'keywords',
            content: 'contact, lorem, ipsum'
        }
    ]
})

</script>

<template>
    <div>
        <h1>Contact</h1>
        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Culpa esse adipisci saepe itaque sunt tempora nam mollitia dignissimos, odio veniam architecto maiores. Recusandae porro nesciunt pariatur accusamus tempora in quae!</p>
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