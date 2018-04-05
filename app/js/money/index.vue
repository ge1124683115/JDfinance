<template lang="html">
    <div>
        <Heador/>
        <Slider/>
        <Ada/>
        <Money/>
        <Adb/>
        <Finance/>
        <Adc/>
        <Footer cname="afooter"/>
        <NavBar/>
    </div>
</template>

<script>
    import Heador  from '../publice/header.vue'
    import Slider  from './mslider.vue'
    import Ada     from './ada.vue'
    import Adb     from './adb.vue'
    import Footer  from '../publice/footer.vue'
    import NavBar  from '../publice/navbar.vue'
    import Money   from "../home/money.vue";
    import Finance from "./finance.vue";
    import Adc     from './adc.vue'
    export default {
        components: {
            Finance,
            Money,
            Heador,
            Slider,
            Ada,
            Adb,
            Adc,
            Footer,
            NavBar
        },
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
