<script setup>
import Navbar from '@/components/navbarComponent.vue';
import Footer from '@/components/footerComponent.vue';
import { products } from '@/assets/js/productdata.js';
</script>




<template>
    <Navbar/>

    <div class="product_container main_container content_container">
        <div class="collection">
        <h2>Our Colletion</h2>
        <p>We have <strong>{{ products.length }}</strong> Shoes in our Collection</p>

            <div class="collection_items">
                <div v-for="(product, index) in products" :key="index">
                    <div class="collection_infor">
                        <div class="img">
                            <img :src="product.image" :alt="`Image of ${product.name}`" />
                        </div>
                        <div class="group">
                            <p>Name: <span>{{ product.name }}</span></p>
                            <p class="price">Ksh. {{ product.price }}</p>
                        </div>
                        <p>Color: <strong>{{ product.color }}</strong></p>
                        <div class="group">
                            <p class="status">Available</p>
                            <p>Size: <strong>{{ product.size }}</strong></p>
                        </div>
                        <button>
                            <a :href="'https://wa.me/254769696309?text=' + encodeURIComponent('Lawbert shoes, inquiry about ' + product.name)" target="_blank">Inquire Now</a>
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <Footer/>
</template>
