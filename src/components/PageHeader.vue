<template>
    <h1 class="page-header">{{ title }}</h1>
</template>

<script setup lang="ts">

defineProps<{
    title: string,
}>()
</script>

<style scoped>
.page-header {
    text-align: center;
    margin-bottom: var(--gutter);
}
</style>
