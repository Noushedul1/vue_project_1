<template>
<!-- start nav  -->
 <ComNav />
 <!-- end nav  -->
 <!-- start banner  -->
 <ComBanner />
 <!-- end banner  -->
 <!-- start chef  -->
 <ComChef />
 <!-- end chef  -->
 <!-- start big burgar -->
 <ComBiggberger />
 <!-- end big burgar -->
 <!-- start Popularpackage  -->
 <ComPopularpackage />
 <!-- end Popularpackage  -->
 <!-- start quote  -->
 <ComQuote />
 <!-- end quote  -->
<!-- start from -->
<ComForm />
<!-- end from  -->
<!-- start footer  -->
<ComFooter />
<!-- end footer  -->

</template>
<script>
import ComNav from './components/Nav.vue';
import ComBanner from './components/Banner.vue';
import ComChef from './components/Chef.vue';
import ComBiggberger from './components/Biggberger.vue';
import ComPopularpackage from './components/Popularpackage.vue';
import ComQuote from './components/Quote.vue';
import ComForm from './components/Form.vue';
import ComFooter from './components/Footer.vue';
    export default{
        components : {ComNav,ComBanner,ComChef,ComBiggberger,ComPopularpackage,ComQuote,ComForm,ComFooter},
        data(){
            return{
                fname : 'akib'
            }
        }
    }
</script>
<style scoped>

</style>
