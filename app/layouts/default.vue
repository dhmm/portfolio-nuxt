<template>
    <div class="container mx-auto max-w-2xl">
        <header class="flex justify-between items-center mt-5">
            <div class="text-xl font-semibold p-2 hover:bg-gray-200">
                <NuxtLink to="/">Moutlou</NuxtLink>
            </div>
            <Menu />
        </header>
        <main class="p-2 mt-10">
            <slot />
        </main>
    </div>
</template>

<script setup>
useHead({
    titleTemplate: ' Moutlou\'s Portfolio | %s',
    link: [
        {
            rel: 'preconnect',
            href: 'https://fonts.googleapis.com'
        },
        {
            rel: 'stylesheet',
            href: 'https://fonts.googleapis.com/css2?family=Roboto&display=swap',
            crossorigin: ''
        }
    ]
})
</script>

<style>
body{
    font-family: 'Roboto';
}
</style>