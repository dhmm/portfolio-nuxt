<template>
    <div>
        <nav>
            <ul>
                <li><NuxtLink to="/">Home page</NuxtLink></li>
                <li><NuxtLink to="/about">About page</NuxtLink></li>
            </ul>
        </nav>
        <h4>This is the custom layout</h4>
        <slot/>
    </div>
</template>