<script setup>
import Navbar from '@/components/navbarComponent.vue'
import Footer from '@/components/footerComponent.vue'
import { products } from '@/assets/js/arrivesdata.js';
</script>


<template>
   <Navbar/>

    <div class="arrives_container main_container content_container">
      <h1>Our New Arrives</h1>

        <div class="collection">
            <p>Here are our new arrives for <strong>(20/09/2024)</strong></p>
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