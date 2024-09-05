<script setup></script>

<template>
    <div class="footer_containter">
       <div class="footer_content">
            <div class="footer_logo">
                <img src="/src/assets/images/shoe.jpg"  width="40px" height="40px" alt="logo Image">
                <p><span>LawBert Shoes</span></p> 
                <p>Step into the Best Shoes at Prices You'll Love! Contact Us Today for Inquiries.</p>
            </div>

            <div class="footer_links">
                <h2>Explore</h2>
                <li><router-link :to="{ name:'products' }">Shoes</router-link></li>
                <li><router-link :to="{ name:'arrives' }">Arrives</router-link></li>
                <li><router-link :to="{ name:'contact' }">Contact</router-link></li>
                <li><router-link :to="{ name:'about' }">About</router-link></li>
            </div>

            <div class="footer_social">
                <h2>Contact</h2>
                <a href="https://wa.me/254799509242?text='Lawbert shoes'">
                    <img src="../assets/images/whatsapp.png" alt="whatapp icon">
                </a>

                <a href="#" target="_blank">
                    <img src="../assets/images/instagram.png" alt="instagram icon">
                </a>

                <div class="contact">
                    <p>Contact us through:</p>
                    <p>+254 769 696 309 / +254 799 509 242</p>
                </div>
            </div>
       </div>

       <hr>

       <div class="footer_copy">
            <p>&COPY; 2024 | LawBert Shoes Collection | All Rights Reserved</p>
       </div>
    </div>
</template>