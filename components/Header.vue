<template>
    <header class="bg-flamingo-700 py-2">
        <main class="container mx-auto flex flex-row justify-between">
            <img src="public/Logo header.png" />
            <div class="text-white text-lg font-bold">
                <nuxt-link to="/">Sina Leather</nuxt-link>
            </div>
            <nav class="flex flex-row justify-end gap-4">
                <nuxt-link to="/Home">Home</nuxt-link>
                <nuxt-link to="/Products">Products</nuxt-link>
                <nuxt-link to="/Contact">Contact</nuxt-link>
                <nuxt-link to="/About">About</nuxt-link>
            </nav>
            
        </main>

    </header>
</template>