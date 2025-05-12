<template>
    <div class="h-full">
        <header class="hero min-h-1/4 bg-cover bg-top lg:bg-center xl:bg-bottom">
            <div class="pt-0 md:pt-2"></div>
            <nav class="mx-auto h-10 w-full md:w-4/5 bg-primary rounded-2xl bg-opacity-30 p-8 backdrop-blur shadow-md shadow-blue hover:shadow-lg hover:shadow-blue-500">
                <ul class="flex items-center justify-around font-bold h-full">
                    <li class="cursor-pointer duration-500 hover:text-yellow-500">Home</li>
                    <span class="h-8 border-2 border-yellow-100"></span>
                    <li class="cursor-pointer duration-500 hover:text-yellow-500">Radar</li>
                    <span class="h-8 border-2 border-yellow-100"></span>
                    <li class="cursor-pointer duration-500 hover:text-yellow-500">Blog</li>
                    <span class="h-8 border-2 border-yellow-100"></span>
                    <li class="px-3 py-2 font-extrabold text-gray-900 bg-green-200 rounded-full cursor-pointer duration-500 hover:bg-opacity-75 hover:text-orange-500">Contact</li>
                </ul>
            </nav>
            <h2 class="pt-24 text-9xl text-center font-bold tracking-wide text-yellow-100">Hello.</h2>
        </header>
        <main>
            <div class="md:pt-16 lg:pt-32"></div>
            <section class="px-12 py-12 md:px-16 lg:px-48 xl:px-72 text-yellow-100">
                <h2 class="text-4xl">I'm Zach <br /> - <br /> Data Engineer and Software Developer</h2>
                <h1 class="py-12 text-6xl">
                    I enjoy solving problems. Frequently praised as <span class="bg-gradient-to-r from-yellow-100 to-yellow-500 bg-clip-text text-transparent font-extrabold tracking-wide"> creative </span> and <span class="bg-gradient-to-r to-yellow-100 from-yellow-500 bg-clip-text text-transparent font-extrabold tracking-wide"> detail-oriented </span> by my peers, I can be relied upon to help your company achieve its goals by providing <span class="text-green-700 font-extrabold tracking-wide"> sustainable </span> and <span class="text-green-700 font-extrabold tracking-wide"> scalable </span> solutions.
                </h1>
            </section>
        </main>
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
    background-image: linear-gradient(rgba(0,0,0,0) 20%, skyblue 80%), url("/assets/img/coding-screen.webp");
    background-color: black;
}
</style>