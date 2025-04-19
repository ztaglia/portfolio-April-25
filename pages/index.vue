<template>
    <div class="h-full">
        <header class="hero h-1/4 bg-cover bg-top">
            <nav class="h-10 bg-primary rounded-xl bg-opacity-30 p-8 backdrop-blur hover:shadow-lg hover:shadow-blue-500">
                <ul class="flex items-center justify-around font-bold h-full">
                    <li>Home</li>
                    <li>Radar</li>
                    <li>Blog</li>
                    <li>Contact</li>
                </ul>
            </nav>
        </header>
        <main></main>
        <footer class="top-[100vh] top-full flex flex-col items-center sticky mt-auto text-gray-600 border-t-2 border-gray-600">
            <p class="text-sm">© 2025 Zachary Taglia</p>
            <div class="ml-auto flex justify-center">
                <a href="https://github.com/ztaglia" target="_blank">
                    <img class="w-8 px-1" src="/assets/img/github-logo.png" alt="">
                </a>
                <a href="https://www.linkedin.com/in/zachary-taglia-35b42222b/" target="_blank">
                    <img class="w-8 px-1" src="/assets/img/linkedin-logo-bnw.png" alt="">
                </a>
            </div>
        </footer>
    </div>
</template>

<script setup lang="ts"></script>

<style scoped>
.hero {
    background-image: url("/assets/img/coding-screen.webp");
    background-color: black;
}
</style>