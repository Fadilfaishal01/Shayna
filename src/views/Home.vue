<template>
  <div class="home">
    <Header />
    <HeroSection />
    <WomanBanner />
    <Instagram />
    <PartnerLogo />
    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
import Header from '@/components/Header.vue'
import HeroSection from '@/components/HeroSection.vue'
import WomanBanner from '@/components/WomanBanner.vue'
import Instagram from '@/components/Instagram.vue'
import PartnerLogo from '@/components/PartnerLogo.vue'
import Footer from '@/components/Footer.vue'


export default {
  name: 'Home',
  components: {
    Header,
    HeroSection,
    WomanBanner,
    Instagram,
    PartnerLogo,
    Footer
  }
}
</script>
