<script setup>
import { ref } from 'vue';

const isNavOpen = ref(false);

const toggleNav = () => {
    isNavOpen.value = !isNavOpen.value;
};
const closeNav = () => {
    isNavOpen.value = false;
};

</script>

<template>
    <div class="nav_container">
        <div class="logo">
            <img src="../assets/images/shoe.jpg" width="40px" height="40px" alt="logo">
            <router-link :to="{ name:'home' }">Lawbert Shoes</router-link>
        </div>
        
        <div class="nav_links" :class="{ 'active': isNavOpen }">
            <ul>
                <li><router-link :to="{ name:'about' }">About</router-link></li>
                <li><router-link :to="{ name:'products' }">Shoes</router-link></li>
                <li> <router-link :to="{ name:'arrives' }">Arrives</router-link> </li>
                <li> <router-link :to="{ name:'contact' }">Contact</router-link></li>
            </ul>
        </div>

        <div class="burger" @click="toggleNav" :class="{ 'active': isNavOpen }">
            <span></span>
            <span></span>
            <span></span>
        </div>
    </div>
</template>