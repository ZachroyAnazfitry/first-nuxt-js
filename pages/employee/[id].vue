<template>
    <div>
        <p>Employee number is {{ id }}</p>
    </div>
</template>

<script setup>
    const { id } = useRoute().params

</script>

<style scoped>

</style>