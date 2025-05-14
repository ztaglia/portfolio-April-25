<template>
<nav class="mx-auto h-10 w-full md:w-4/5 bg-primary rounded-2xl bg-opacity-30 p-8 backdrop-blur shadow-md shadow-blue hover:shadow-lg hover:shadow-blue-500">
    <ul class="flex items-center justify-around font-bold h-full">
        <li>
            <NuxtLink to="/" class="cursor-pointer duration-500 hover:text-yellow-500" 
            active-class="text-yellow-300">
            Home
        </NuxtLink>
        </li>
        <span class="h-8 border-2 border-yellow-100"></span>
        <li>
            <NuxtLink to="/radar" class="cursor-pointer duration-500 hover:text-yellow-500" 
            active-class="text-yellow-300">
            Radar
        </NuxtLink>
        </li>
        <span class="h-8 border-2 border-yellow-100"></span>
        <li>
            <NuxtLink to="/blog" class="cursor-pointer duration-500 hover:text-yellow-500" 
            active-class="text-yellow-300">
            Blog
        </NuxtLink>
        </li>
        <span class="h-8 border-2 border-yellow-100"></span>
        <li>
            <NuxtLink 
            to="/contact" 
            class="px-3 py-2 font-extrabold text-gray-900 bg-green-200 rounded-full cursor-pointer duration-500 hover:bg-opacity-75 hover:text-orange-500" 
            active-class="bg-orange-500">
            Contact
            </NuxtLink>
        </li>
    </ul>
</nav>
</template>