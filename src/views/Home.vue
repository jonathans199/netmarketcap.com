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
            
        </div>
    </section>
    <section class="intro">
        <div class="intro-left">
            <img src="@/assets/img/logo_icon.png" alt="">
        </div>
        <div class="intro-right">
            <h1>WHAT IS NETMARKETCAP...</h1>
            <p>
                <p>It is the flagship product of an international company with physical offices in Germany, which proposes to implement its tools to increase the results in the securities market of Cryptocurrencies through Trading, guided by world experts. <p> Netmarketcap is also a tool focused on improving relational systems between investors and a team of professional traders in cryptocurrencies, with the best strategies and the best conditions based on trust with the goal of win-win as the fundamental focus of our company.</p>
                <p>We are convinced that with strategic planning this emerging market can take us to new levels of sustainable profits over time.</p>
            </p>
        </div>
    </section>

    <section class="financial-support">
        <h1>Netcoin.io</h1>
        
    </section>

    <section style="text-align: center">
        <h1 style="padding-top: 30px; font-size: 30px;">CORE ENGINEERS</h1>
        <p style="font-size: 20px">Motivated developers move projects forward more than anyone else. Netcoin.io Developers have a relentless desire to learn and grow, and they consistently push themselves forward.</p>
        <div class="products">
            
            <div class="products__item">
                <img src="@/assets/img/netcoin1.png" alt="">
                <h1>JASON SNAP</h1>
                <p>Working with Netcoin since October 2013. 6 years with Business Development &amp; Startups, 4 years with Photoshop, 3 years with WordPress </p>
            </div>
            <div class="products__item">
                <img src="@/assets/img/netcoin2.png" alt=""style="width: 300px">
                <h1>Peter Liang</h1>
                <p>Working with Netcoin since March 2014.  10+ years with C and C++ code, 4 years in cryptos and development, 2 years with linux,apache,mysql and php</p>
            </div>
            <div class="products__item">
                <img src="@/assets/img/netcoin3.png" alt="" >
                <h1>Jason K</h1>
                <p>Working with Netcoin since August 2015. 8+ Years in Business Development & Startups, 7+ years in Real Estate Development</p>
            </div>
        </div>
    </section>

    <section class="divider">
    </section>

    <section class="plans">
        <div class="grid"></div>
        <div class="plan">
            <img src="@/assets/img/bit_icn.png" alt="">
            <h1 class="plan-title">PROFITABLE</h1>
            <p>Your investment is assured in Netmarketcap. Our international traders give us the peace of mind necessary to offer you the best monthly performance rates. The operations of our traders are based on technical analysis and functional analysis to ensure the best results</p>
            <button v-on:click="openTab('http://app.netmarketcap.com/#/register')">Sign up</button>
        </div>
        <div class="plan">
            <img src="@/assets/img/mob_cash.png" alt="">
            <h1 class="plan-title">PAYMENTS</h1>
            <p>Our automatic system of collections and payments of profitability allows us to ensure compliance with one hundred percent in the dates and amounts of payments to each user. We work hand in hand with experts in systems of generation of recurrent payments combined with dynamic payments, according to the needs of the market.</p>
            <button v-on:click="openTab('http://app.netmarketcap.com/#/register')">Sign up</button>
        </div>
        <div class="plan">
            <img src="@/assets/img/bit_cir.png" alt="">
            <h1 class="plan-title">SECURITY</h1>
            <p>Our Company is backed by world-class companies that work night and day to keep the portal insured. We want to generate the necessary trust in our investors and for this reason we do not save efforts or money to obtain the best in security.</p>
            <button v-on:click="openTab('http://app.netmarketcap.com/#/register')">Sign up</button>
        </div>
    </section>

    <section class="financial-support">
        <h1>Financial Support</h1>
    </section>

    <section>
        <div class="products">
            <div class="products__item">
                <img src="@/assets/img/nodes.png" alt="">
                <h1>MASTER NODES</h1>
                <p>A masternode is a type of complete node, but its functions go beyond retransmitting and verifying transactions through the network. They have gained momentum because they can be considered as an investment to obtain a source of passive income, constant and quickly put into operation.</p>
            </div>
            <div class="products__item">
                <img src="@/assets/img/robot.png" alt="">
                <h1>MINING</h1>
                <p>The bitcoin miners are the key figure in the blockchain that supports this cryptocurrency, and the approximately 2000 existing cryptocurrencies (and rising). And no, they are not people, but machines. Our Company has experts in modern mining systems to focus and optimize investments.</p>
            </div>
            <div class="products__item">
                <img src="@/assets/img/analytics.png" alt="">
                <h1>TRADING</h1>
                <p>The cryptocurrencies are one of the most profitable investments of the moment, being the Bitcoin the one with the highest volume and volatility. The opportunity to trade with cryptocurrencies is fantastic, since it allows you to invest 24 hours every day of the week. Our professional traders assure us the necessary profitability to make us sustainable over time.</p>
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
        <div class="packages-container">
            <div class="package package-0">
                <h2>Promo</h2>
                <p>$50</p>
            </div>
            <div class="package package-1">
                <h2>Basic</h2>
                <p>$100</p>
            </div>
            <div class="package package-2">
                <h2>Medium</h2>
                <p>$250</p>
            </div>
            <div class="package package-3">
               <h2>Platinum</h2>
                <p>$500</p>
            </div>
            <div class="package package-4">
                <h2>Gold</h2>
                <p>$1,000</p>
            </div>
        </div>
    </section>

    
    <!-- <section class="contact">
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
    </section> -->
    
    
    
    
    <!-- <section>
        <div class="faq">
            <div class="faq-title">
                <h1>FREQUENT ASK QUESTIONS</h1>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Eaque, itaque.</p>
            </div>
            <div class="faq">
                <button>FAQ</button>
            </div>
        </div>
    </section> -->


        
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
  },
  methods: {
    openTab(url){
      window.open(url, '_blank');
    }
  }
}

</script>
