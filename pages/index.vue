<template>
        <main>
            <div class="md:pt-16 lg:pt-32"></div>
            <section class="px-12 py-12 md:px-16 lg:px-48 xl:px-72 text-yellow-100">
                <h2 class="text-4xl">I'm Zach <br /> - <br /> Data Engineer and Software Developer</h2>
                <h1 class="py-12 text-6xl">
                    I enjoy solving problems. Frequently praised as <span class="bg-gradient-to-r from-yellow-100 to-yellow-500 bg-clip-text text-transparent font-extrabold tracking-wide"> creative </span> and <span class="bg-gradient-to-r to-yellow-100 from-yellow-500 bg-clip-text text-transparent font-extrabold tracking-wide"> detail-oriented </span> by my peers, I can be relied upon to help your company achieve its goals by providing <span class="text-green-700 font-extrabold tracking-wide"> sustainable </span> and <span class="text-green-700 font-extrabold tracking-wide"> scalable </span> solutions.
                </h1>
            </section>
            <section class="py-12">
                <h2 class="text-4xl text-center text-yellow-100 md:text-5xl lg:text-6xl">About Me</h2>
                <div class="pt-4 lg:pt-8"></div>
                <p class="px-12 text-lg md:text-xl">
                    Hello! I’m a full-stack web developer and machine learning engineer with a B.S. in Data Science 
                    from the <span class="bg-gradient-to-r from-blue-600 to-yellow-400 bg-clip-text text-transparent font-bold"> University of Michigan in Ann Arbor. </span> 
                    I specialize in building intuitive web applications and developing machine learning models that drive impactful insights. 
                    My technical toolkit includes Numpy, Pandas, SQL (SQLite, MongoDB), C++, JavaScript, HTML/CSS, React.js, Next.js, Vue.js, TensorFlow, Flask, and Tableau.
                    I’m passionate about creating tools that make complex systems accessible, from real-time music recognition engines to personalized AI interview bots. 
                    I love working on projects that blend technical depth with human-centered design, and I thrive in collaborative environments where innovation and storytelling meet data.
                </p>
            </section>
            <section class="py-12">
                <h2 class="px-5 pb-6 text-4xl text-yellow-100 md:text-5xl">My Work</h2>
                <div class="grid grid-cols-1 lg:grid-cols-2 xl-grid-cols-3 gap-4">
                    <div class="h-12 bg-black">
                        <img src="" alt="">
                        <div></div>
                    </div>
                    <div class="h-12 bg-black">
                        <img src="" alt="">
                        <div></div>
                    </div>
                    <div class="h-12 bg-black">
                        <img src="" alt="">
                        <div></div>
                    </div>
                </div>
            </section>
        </main>
</template>

<script setup lang="ts">
definePageMeta({
    layout: "home",
})
</script>