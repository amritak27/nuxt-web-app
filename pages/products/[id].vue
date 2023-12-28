<template>
    <div>
        <p>Product details for {{ id }}</p>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Error voluptatum reprehenderit, doloribus quis nulla
            pariatur tempora sapiente molestiae laboriosam ipsa?</p>
    </div>
</template>

<script setup>
const { id } = useRoute().params
definePageMeta({
    layout: 'products'
})
</script>

<style scoped></style>