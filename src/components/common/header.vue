<template>
    <div class="header">
        <TopBanner />
        <TopNavigation />
        <div class="search">
            <img :src="'./images/shopper.png'" alt="" class="logo">
        </div>
        <div class="vendor-menu"></div>
        <div class="home-banner"></div>
        <div class="help"></div>
        <div class="selected-products"></div>
        <div class="featured-products"></div>
        <div class="latest-blog"></div>
        <div class="keywords"></div>
        <div class="footer"></div>
        <div class="copyright"></div>
    </div>
</template>

<script>
import TopBanner from "@/components/landing-page/top-banner.vue";
import TopNavigation from "@/components/common/top-navigation.vue";


export default {
    name: 'header',
    components: {
        TopBanner,
        TopNavigation
    }
}
</script>

<style>
.search {
    height: 80px;
    background-color: aqua;
}
.vendor-menu {
    height: 50px;
    background-color: saddlebrown;
}
.home-banner {
    height: 480px;
    background-color: seagreen;
}
.help {
    height: 160px;
    background-color: lightcoral;
}
.selected-products {
    height: 640px;
    background-color: goldenrod;
}
.featured-products {
    height: 800px;
    background-color: cornflowerblue;
}
.latest-blog {
    height: 320px;
    background-color: red;
}
.keywords {
    height: 190px;
    background-color: teal;
}
.footer {
    height: 250px;
    background-color: hotpink;
}
.copyright {
    height: 50px;
    background-color: purple;
}
</style>