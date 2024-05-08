<template>
   <footer class="bg-gray-200 border-t  text-center border-gray-300 p-8">
    <div class="mb-6 text-lg"> 
        <nuxt-link to="/" class="roboto">Sina leather</nuxt-link>
    </div>
    <nav class="flex flex-row justify-center gap-4">
        <nuxt-link to="/Home">Home</nuxt-link>
        <nuxt-link to="Products">Products</nuxt-link>
        <nuxt-link to="About">About</nuxt-link>
        <nuxt-link to="Contact">Contact</nuxt-link>
    </nav>


    <div>
        <nuxt-link to="/page4">  
            <button class="bg-sky-600 text-white px-6 py-2">Say Hi</button>
        </nuxt-link>
      
    </div>
    <div>
        <a href="https://microsoft.com">  
            <button class="bg-sky-600 text-white px-6 py-2">Go to Microsoft</button>
        </a>
    </div>
   </footer>
</template>
