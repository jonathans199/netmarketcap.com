<template>
  <div>
    <Header/>
    <section> 
        <div class="video__overlay"></div>
        <video
            autoplay
            loop
            playsinline 
            class="video" 
            title="Net Market cap video"
            muted="muted"
            poster="">
            <!-- <source src="@/assets/cryptovideo.webm" type="video/webm"/> -->
            <source src="@/assets/bkico.mp4" type="video/mp4" />
            <!-- <source src="/viviela_video.ogv" type="video/ogg" />     -->
            <p>ooooooppsss its seems your browser is not supported to display this awesome background video <a href="https://www.google.com/chrome/" target="_blank"> Download and use google chrome</a> </p>       
        </video>


        <div class="hero-text">
            <h4 class="subtext">FOR</h4>
            <h1 class="main-text">SMART</h1>
            <h1 class="submain-text">INVESTORS</h1>
            <div class="social_icons">
                <a class="fab fa-facebook-square" href="https://www.facebook.com/vivielashoes" target="_blank"></a>&nbsp;
                <a class="fab fa-instagram" href="https://www.instagram.com/viviela.official/?hl=en" target="_blank"></a>&nbsp;
                <a class="fab fa-youtube" href="https://www.youtube.com/user/vivielalondon" target="_blank"></a>
            </div>
        </div>
    </section>
    <section class="intro">
        <div class="intro-left">
            <img src="@/assets/img/logo_icon.png" alt="">
        </div>
        <div class="intro-right">
            <h1>WE ARE A COMPANY...</h1>
            <p><b>Why do we use it?</b> </br> 
            It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. The point of using Lorem Ipsum is that it has a more-or-less normal distribution of letters, as opposed to using ‘Content here, content here’, making it look like readable English. Many desktop publishing packages and web page editors now use Lorem Ipsum as their default model text, and a search for ‘lorem ipsum’ will uncover many web sites still in their infancy. Various versions have evolved over the years, sometimes by accident, sometimes on purpose (injected humour and the like).</p>
        </div>
    </section>

    <section class="divider">
    </section>

    <section class="plans">
        <div class="grid"></div>
        <div class="plan">
            <img src="@/assets/img/bit_icn.png" alt="">
            <h1 class="plan-title">secure</h1>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Perferendis, accusantium numquam? Ea a id dolores ipsa dicta deserunt optio adipisci.</p>
            <button>read more</button>
        </div>
        <div class="plan">
            <img src="@/assets/img/mob_cash.png" alt="">
            <h1 class="plan-title">secure</h1>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Perferendis, accusantium numquam? Ea a id dolores ipsa dicta deserunt optio adipisci.</p>
            <button>read more</button>
        </div>
        <div class="plan">
            <img src="@/assets/img/bit_cir.png" alt="">
            <h1 class="plan-title">secure</h1>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Perferendis, accusantium numquam? Ea a id dolores ipsa dicta deserunt optio adipisci.</p>
            <button>read more</button>
        </div>
    </section>

    <section class="financial-support">
        <h1>Financial Support</h1>
    </section>

    <section>
        <div class="products">
            <div class="products__item">
                <img src="@/assets/img/analytics.png" alt="">
                <h1>subsection</h1>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Maiores, minima?</p>
            </div>
            <div class="products__item">
                <img src="@/assets/img/robot.png" alt="">
                <h1>subsection</h1>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Maiores, minima?</p>
            </div>
            <div class="products__item">
                <img src="@/assets/img/nodes.png" alt="">
                <h1>subsection</h1>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Maiores, minima?</p>
            </div>
        </div>
    </section>

    <!-- <section class="crpto-prices">
        <h1>crypto currency prices</h1>
        <div class="top3">
            <div class="price">
                <h1>bitcoin</h1>
                <img src="" alt="">
                <h2>current Price</h2>
            </div>
        </div>
    </section> -->

    <section class="packages">
        <h1>Investment Packages</h1>
        <img src="@/assets/img/esquema.png" alt="">
    </section>

    
    <section class="contact">
        <h1>STAY IN TOUCH</h1>
       <form class="container">
            <div class="form-row">
                <div class="form-group col-md-6 ">
                    <input type="email" class="" id="inputEmail4" placeholder="Email">
                </div>
                <div class="form-group col-md-6">
                    <input type="password" class="" id="inputPassword4" placeholder="Password">
                </div>
            </div>           
            <div class="form-group">
                <input type="text" class="" id="inputAddress2" placeholder="message">
            </div>
            <button type="submit" >SEND MESSAGE</button>
        </form>
    </section>
    
    
    
    
    <section>
        <div class="faq">
            <div class="faq-title">
                <h1>FREQUENT ASK QUESTIONS</h1>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Eaque, itaque.</p>
            </div>
            <div class="faq">
                <button>FAQ</button>
            </div>
        </div>
    </section>


        
    <Footer/>
  </div>
</template>

<script>

import Header from '@/components/Header'
import Footer from '@/components/Footer'

export default {
  name: 'Home',
  components: {
    Footer,
    Header
  }
}

</script>
