<script setup>
import Navbar from '@/components/navbarComponent.vue'
import Footer from '@/components/footerComponent.vue'
</script>

<template>
    <Navbar/>

    <div class="contact_container main_container">
        <h1 class="title"><span class="brackets">Contact Us</span></h1>
        <div class="contact_content">
            <div class="contact_infor">
              <p> lawbertshoes@gmail.com</p>
              <p> +254 799 509 242 / +254 769 696 309</p>
            </div>

            <div class="contact_form">
                <form  name="contact" method="POST" data-netlify="true">
                    <input type="hidden" name="form-name" value="contact">

                    <div class="input_group">
                        <div class="name">
                            <input type="text" name="first_name" id="first_name" placeholder="Enter first name" required>
                            <input type="text" name="last_name" id="last_name"  placeholder="Enter last name" required>
                        </div>
                        <div class="input_group">
                            <input type="email" name="email" id="email"   placeholder="Enter you email" required>
                        </div>
                        <div class="input_group">
                            <textarea name="message" id="message" cols="7" rows="5"  placeholder="Type you message here" required></textarea>
                        </div>
                    </div>
                    <button type="submit">Submit</button>
                </form>
            </div>
        </div>
    </div>

    <Footer/>
</template>
