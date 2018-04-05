<template lang="html">
    <div>
        <Heador/>
        <Slider/>
        <Daliy/>
        <In/>
        <More/>
        <Footer cname="afooter"/>
        <NavBar/>
    </div>
</template>

<script>
    import Heador  from '../publice/header.vue'
    import Slider  from './rslider.vue'
    import Footer  from '../publice/footer.vue'
    import NavBar  from '../publice/navbar.vue'
    import Daliy   from "./daliy";
    import In from "./in";
    import More from "./more";
    export default {
        components: {More, In, Daliy, Heador, Slider, Footer, NavBar},
    }
</script>

<style lang="scss">
    .afooter {
        margin-top: 0 !important;
        ul {
            li:first-child {
                display: none;
            }
        }
    }
</style>
