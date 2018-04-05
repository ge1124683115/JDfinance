<template lang="html">
    <div>
        <Header/>
        <Slider/>
        <Welfare/>
        <Service/>
        <Footer/>
        <Navbar/>
    </div>
</template>
<script>
    import Header from "../publice/header";
    import Slider from "./islider.vue";
    import Footer from "../publice/footer";
    import Navbar from "../publice/navbar";
    import Welfare from "./welfare";
    import Service from "./service";
    export default {
        components: {Service, Welfare, Navbar, Footer, Slider, Header}
    }
</script>