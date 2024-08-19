<template>
    <nav class="font-mono">
        <ul class="flex space-x-4">
            <li>
                <NuxtLink to="/" class="menu-item">Home</NuxtLink>
            </li>
            <li>
                <NuxtLink to="/projects" class="menu-item">Projects</NuxtLink>
            </li>
            <li>
                <NuxtLink to="/about" class="menu-item">About</NuxtLink>
            </li>
        </ul>
    </nav>
</template>

<style scoped>
    .menu-item
    {
        @apply p-1 hover:bg-gray-200
    }
</style>