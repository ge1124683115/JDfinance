<template lang="html">
    <div>
        <Heador/>
        <Slider/>
        <Novice/>
        <Borrow/>
        <Money/>
        <Product/>
        <Life/>
        <Footer/>
        <NavBar/>
    </div>
</template>

<script>
    import Heador  from '../publice/header.vue'
    import Slider  from './hslider.vue'
    import Novice  from './novice.vue'
    import Borrow  from './borrow.vue'
    import Money   from './money.vue'
    import Product from './product.vue'
    import Life    from './life.vue'
    import Footer  from '../publice/footer.vue'
    import NavBar  from '../publice/navbar.vue'
    export default {
        components: {
            Heador,
            Slider,
            Novice,
            Borrow,
            Money,
            Product,
            Life,
            Footer,
            NavBar
        },
    }
</script>
