<template>
    <header>
        <img class="header__logo" alt="NetMarketCap logo" src="@/assets/img/netmarketcap-logo-widewht.png">
        <div class="menu">
            <!-- <a href="#">About us</a>
            <a href="#">Plans</a>
            <a href="#">Support</a>
            <a href="#">Products</a>
            <a href="#">Contact</a> -->
            <a href="https://play.google.com/store/apps/details?id=xyz.lioncomputer.netmarketcap" target="_blank"><img src="@/assets/img/gplay.png" alt="" style="width: 150px"></a>
            <button v-on:click="openTab('http://app.netmarketcap.com/#/register')">REGISTER</button>
            <button v-on:click="openTab('http://app.netmarketcap.com/#/login')">LOGIN</button>
        </div>
    </header>
</template>

<script>
export default {
    methods: {
    openTab(url){
      window.open(url, '_blank');
    }
}
}
</script>

