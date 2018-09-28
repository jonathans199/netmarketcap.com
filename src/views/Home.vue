<template>
  <div>
      <Header/>
        <div class="video__overlay"></div>
    <video
        autoplay
        loop
        playsinline 
        class="video" 
        title="viviela_video"
        muted="muted"
        poster="">
          <!-- <source src="@/assets/cryptovideo.webm" type="video/webm"/> -->
          <source src="@/assets/bkico.mp4" type="video/mp4" />
          <!-- <source src="/viviela_video.ogv" type="video/ogg" />     -->
          <p>ooooooppsss its seems your browser is not supported to display this awesome background video <a href="https://www.google.com/chrome/" target="_blank"> Download and use google chrome</a> </p>       
    </video>


    <div class="hero-text">
        <button v-b-modal.formModal type="button" class="home__button">
                <h1 class="preaccess">GET PRE-ACCESS</h1>
        </button>
      <span class="subtext">
       <a href="mailto:info@viviela.com"> info@viviela.com</a>
      </span>
      <div class="social_icons">
        <a class="fab fa-facebook-square" href="https://www.facebook.com/vivielashoes" target="_blank"></a>&nbsp;
        <a class="fab fa-instagram" href="https://www.instagram.com/viviela.official/?hl=en" target="_blank"></a>&nbsp;
        <a class="fab fa-youtube" href="https://www.youtube.com/user/vivielalondon" target="_blank"></a>
      </div>
    </div>

       <!-- Modal -->
            <b-modal hide-footer hide-header id="formModal" ref="formModal">
                  <div class="modal-header">
                    <h1 class="modal-title" id="exampleModalLabel">GET PRE-ACCESS</h1>
                    <button type="button" class="home__button" v-on:click="closeModal()" aria-label="Close">
                      <span aria-hidden="true">&times;</span>
                    </button>
                  </div>
                  <div class="modal-body">
                    <form @submit="onSubmit" @reset="onReset" v-if="show">
                      <div class="form-row">
                        <div class="col your_email">
                          <input 
                          type="text" 
                          class="email_capture" 
                          placeholder="FULL NAME"
                          v-model="form.name">
                        </div>
                        <div class="col your_email">
                          <input 
                          type="text" 
                          class="email_capture" 
                          placeholder="YOUR EMAIL"
                          v-model="form.email">
                        </div>
                        <div class="col your_email">
                          <input 
                          type="text" 
                          class="email_capture" 
                          placeholder="INSTAGRAM"
                          v-model="form.instagram">
                        </div>
                        <div class="col your_email">
                          <input 
                          type="text" 
                          class="email_capture" 
                          placeholder="SHOE SIZE"
                          v-model="form.shoe_size">
                        </div>
                        <!-- <div class="col">
                          <button class="home__button" type="submit" >SUBMIT</button>
                        </div> -->
                      </div>
                      <div class="modal-footer">
                        <button type="button" class="home__button" v-on:click="closeModal()">CLOSE</button>
                        <button type="submit" class="home__button">SEND</button>
                      </div>


                    </form>
                  </div>
                  
        
          
            </b-modal>




    <!-- <section class="hero">
        <div class="carousel-caption custom-caption d-md-block">
            <div class="custom-caption__slide-num">for</div>
            <div class="custom-caption__slide-heading">SMART</div>
            <div class="custom-caption__slide-sub-heading">INVESTORS</div>
        </div>

        <div id="carouselExampleIndicators" class="carousel slide custom-slide" data-ride="carousel">
            <ol class="carousel-indicators">
                <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
                <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
            </ol>
            <div class="carousel-inner">
                <div class="carousel-item active">
                <img class="d-block w-100" src="https://placeimg.com/1000/980/tech/grayscale" alt="First slide">
                    
                </div>
                <div class="carousel-item">
                <img class="d-block w-100" src="https://placeimg.com/1000/980/arch/grayscale" alt="Second slide">
              
                </div>
                <!-- <div class="carousel-item">
                <img class="d-block w-100" src="..." alt="Third slide">
                </div> -->
            <!-- </div>
            <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="sr-only">Previous</span>
            </a>
            <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="sr-only">Next</span>
            </a>
        </div>
        </section> -->

        <!-- <section class="intro">
            <div class="intro-left">
                <img src="@/assets/img/logo_icon.png" alt="">
            </div>
            <div class="intro-right">
                <img class="intro-logo" src="@/assets/img/your-logo.png" alt="">
            </div>
            
        </section>

        <section class="divider2">
            <button class="btn outline-success divider2-btn">BUTTON</button>
        </section>

        <section class="shop container">
            <h1>SHOP NOW</h1>
            <h2>Subtext</h2>
            <div class="shop-shoes">
                <img src="@/assets/img/intro-shoe.jpg" alt="" class="shoe">
                <img src="@/assets/img/intro-shoe.jpg" alt="" class="shoe">
                <img src="@/assets/img/intro-shoe.jpg" alt="" class="shoe">
                <img src="@/assets/img/intro-shoe.jpg" alt="" class="shoe">
                <img src="@/assets/img/intro-shoe.jpg" alt="" class="shoe">
                <img src="@/assets/img/intro-shoe.jpg" alt="" class="shoe">
                <img src="@/assets/img/intro-shoe.jpg" alt="" class="shoe">
                <img src="@/assets/img/intro-shoe.jpg" alt="" class="shoe">
            </div>
            <button class="btn vv-button">SHOP MORE</button>
        </section>

        <section class="men-shoes">
            <div class="container men-shoes-content">
                <img class="" src="@/assets/img/your-logo.png" alt="">
                <h3>SUBTEXT</h3>
                <button class="btn vv-button">SHOP MORE</button>
            </div>
        </section>
        <Footer/> -->
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
