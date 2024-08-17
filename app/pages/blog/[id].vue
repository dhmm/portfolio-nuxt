<template>
    <div>
        We are inside of a blog!
    </div>
    <div>
        The <b>id</b> is : <b><u>{{ route.params.id }}</u></b>
    </div>
</template>

<script setup>
// ## We will use the composable useRoute
const route = useRoute();
console.log(route);
</script>