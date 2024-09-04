<script setup>
import Navbar from '@/components/navbarComponent.vue'
import Footer from '@/components/footerComponent.vue'
</script>


<template>
    <Navbar/>

    <div class="about_container main_container">
        <h1>About Us</h1>

        <div class="about_history">
            <div class="history">
                <p>Founded with a passion for footwear and customer satisfaction, LawBert began as a small, 
                    dedicated shop committed to offering high-quality, stylish, and affordable shoes. Over
                    the years, we’ve grown into a trusted name in the industry, consistently prioritizing 
                    comfort and exceptional service. Our journey has been driven by our commitment to
                    making every customer’s experience memorable and enjoyable, and we continue to build on 
                    our legacy with every pair of shoes we offer.
                </p>
            </div>
            <div class="image">
                <img src="/src/assets/images/img.jpg" alt="logo image">
            </div>
        </div>

        <div class="Our_moto main_container">
            <h1>Our Mission & Vission</h1>

            <div class="lawbert_vission">
                <div class="mission">
                    <h3> Our Mission</h3>
                    <p>To provide exceptional service and a diverse selection of high-quality shoes, ensuring every customer 
                        finds the perfect fit and enjoys a satisfying shopping experience.
                    </p>
                </div>

                <div class="vission">
                    <h3>Our Vision</h3>
                    <p>To be the leading destination for stylish and affordable footwear, setting 
                        the standard for comfort and quality in the industry.
                    </p>
                </div>
            </div>
        </div>
    </div>
    <Footer/>
</template>

