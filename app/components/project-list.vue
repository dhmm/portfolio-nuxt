<template>
    <div>
        Projects
    </div>
    <section v-if="pending">Loading...</section>
    <section v-else-if="error">Something gone wrong !!!</section>
    <section v-else="data">Projects will shown here...</section>
</template>

<script setup>
const { error, pending, data } = await useFetch('https://api.github.com/users/dhmm/repos');
</script>