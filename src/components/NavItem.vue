<template>
    <span class=nav-item>
        <RouterLink :to="'/' + route">{{ title }}</RouterLink>
    </span>
</template>

<script setup lang="ts">
import { RouterLink } from 'vue-router'

defineProps<{
    title: string,
    route: string
}>()
</script>

<style scoped>
.nav-item {
    color: var(--banner-color);
    text-transform: uppercase;
}

a {
    color: var(--banner-color);
    text-decoration: none;
}

:visited {
    color: var(--banner-color);
}
</style>
