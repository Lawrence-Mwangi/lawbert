<script setup>
import { products } from '@/assets/js/productdata.js';
</script>


<template>
    <div class="content_container main_container">
        <div class="content_items">
            <div class="content_infor">
                <h3>Why choose Lawbert Shoes</h3>
                <p>Choose LawBert Shoes for unmatched comfort, style, and affordability. We offer a curated selection of high-quality
                    footwear to suit every occasion, all at prices you’ll love. Experience exceptional customer service and find the
                    perfect pair that fits your style and budget
                </p>
                <p>You are always welcomed to explore our collection and find your perfect pair!</p>
            </div>
            <div class="img">
                <img src="/src/assets/images/img.jpg" alt="logo">

                <div class="text">
                    <p>Lawbert Shoes collection</p>
                </div>
            </div>
        </div>


        <div class="collection main_container">
            <h2>Our collection</h2>
        
            <div class="collection_items">
                <div v-for="(product, index)  in products.slice(0, 4)" :key="index">
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

            <div class="call_action">
                <button><router-link :to="{ name:'products' }">Explore More</router-link></button>
            </div>
        </div>

        <div class="infor">
            <h2>Experience the Best in Shoes and Service with Us!</h2>
            <p>Thank you to all our wonderful customers for your continued support! We appreciate you and warmly welcome you to
                keep shopping with us for the best in footwear and service.
            </p>
            <strong>"Thank you to all our valued customers for your incredible support!!!"</strong>
        </div>
    </div>
</template>