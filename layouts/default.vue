<template>
    <div class="h-full">
        <header class="hero min-h-1/4 bg-cover bg-top lg:bg-center xl:bg-bottom">
            <div class="pt-0 md:pt-2"></div>
            <TopNav />
        </header>
        <main>
            <slot />
        </main>
        <Footer />
    </div>
</template>

<script setup lang="ts"></script>

<style scoped>
    .hero {
        background-image: linear-gradient(rgba(0,0,0,0) 20%, skyblue 80%), url("/assets/img/coding-screen.webp");
        background-color: black;
    }
</style>