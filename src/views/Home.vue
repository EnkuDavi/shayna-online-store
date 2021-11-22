<template>
  <div class="home">
    <HeaderShayna/>
    <CarouselHero/>
     <ProductCarousel/>
     <InstaShayna/>
     <PartnerLogo/>
     <FooterShayna/>
  </div>
</template>

<script>
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderShayna from '@/components/HeaderShayna.vue'
import CarouselHero from '@/components/CarouselHero.vue'
import ProductCarousel from '@/components/ProductCarousel.vue'
import InstaShayna from '@/components/InstaShayna.vue'
import PartnerLogo from '@/components/PartnerLogo.vue'
import FooterShayna from '@/components/FooterShayna'

export default {
  name: 'Home',
  components: { 
    HeaderShayna, 
    CarouselHero,
    ProductCarousel,
    InstaShayna,
    PartnerLogo,
    FooterShayna
  }
}
</script>
