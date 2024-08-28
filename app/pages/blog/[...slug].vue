<template>
    <article class="prose dark:prose-invert">
        <ContentDoc/>
    </article>
</template>

<script setup>
// ## We will use the composable useRoute
const route = useRoute();
console.log(route.params.slug);
</script>