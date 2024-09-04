<script setup>
import Navbar from '@/components/navbarComponent.vue'
import Hero from '@/views/HeroView.vue'
import Content from '@/components/contentComponent.vue'
import Footer from '@/components/footerComponent.vue'
</script>

<template>
    <Navbar/>

    <div class="hero_content" id="Hero">
        <Hero/>
    </div>

    <div class="main_container" id="Content">
        <Content/>
    </div>

    <Footer/>
</template>