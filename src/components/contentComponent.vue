<script setup></script>


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
                <div class="collection_infor">
                    <div class="img">
                        <img src="/src/assets/images/image12.jpeg" alt="shoe Image">
                    </div>
                    <div class="group">
                        <p>Name: <span>J1 low cut</span></p>
                        <p class="price">Ksh. 1,400</p>
                    </div>
                    <p>Color: <strong>White & Red</strong></p>
                    <div class="group">
                        <p class="status">Available</p>
                        <p>Size: <strong>No.36</strong></p>
                    </div>
                    <button>
                        <a href="https://wa.me/254769696309?text='Lawbert shoes'" target="_blank">Inquire Now</a>
                    </button>
                </div>

                <div class="collection_infor">
                    <div class="img">
                        <img src="/src/assets/images/image11.jpeg" alt="shoe Image">
                    </div>
                    <div class="group">
                        <p>Name: <span>Nike SB</span></p>
                        <p class="price">Ksh. 1,400</p>
                    </div>
                    <p>Color: <strong>White & Black</strong></p>
                    <div class="group">
                        <p class="status">Available</p>
                        <p>Size: <strong>No.41</strong></p>
                    </div>
                    <button>
                        <a href="https://wa.me/254769696309?text='Lawbert shoes'" target="_blank">Inquire Now</a>
                    </button>
                </div>

                <div class="collection_infor">
                    <div class="img">
                        <img src="/src/assets/images/image9.jpeg" alt="shoe Image">
                    </div>
                    <div class="group">
                        <p>Name: <span>Air Force</span></p>
                        <p class="price">Ksh. 1,800</p>
                    </div>
                    <p>Color: <strong>Black</strong></p>
                    <div class="group">
                        <p class="status ">Available</p>
                        <p>Size: <strong>No.42</strong></p>
                    </div>
                    <button>
                        <a href="https://wa.me/254769696309?text='Lawbert shoes'" target="_blank">Inquire Now</a>
                    </button>
                </div>

                <div class="collection_infor">
                    <div class="img">
                        <img src="/src/assets/images/image6.jpeg" alt="shoe Image">
                    </div>
                    <div class="group">
                        <p>Name: <span>Nike SB</span></p>
                        <p class="price">Ksh. 1,800</p>
                    </div>
                    <p>Color: <strong>Blue & Purple</strong></p>
                    <div class="group">
                        <p class="status">Available</p>
                        <p>Size: <strong>No.38</strong></p>
                    </div>
                    <button>
                        <a href="https://wa.me/254769696309?text='Lawbert shoes'" target="_blank">Inquire Now</a>
                    </button>
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