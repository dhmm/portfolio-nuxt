<template>
    <div>
        <h2 class="text-2xl font-semibold mb-10">Projects</h2>
        <ProjectList/>
    </div>
</template>
<script setup>
const { error, pending, data } = await useFetch('https://api.github.com/users/dhmm/repos');
console.log(data);

useHead({
    title: 'Projects'
})
</script>