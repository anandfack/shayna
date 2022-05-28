<template>
<div class="home">
<!-- Memanggil Components -->
<HeaderShayna />
<CarouselShayna />
<WomenBannerShayna />
<InstaShayna />
<PartnerLogoShayna />
<FooterShayna />
<!-- Akhir Memanggil Components -->
</div>
</template>

<script>
// Import Name dari file Components
import HeaderShayna from '@/components/HeaderShayna.vue'
import CarouselShayna from '@/components/CarouselShayna.vue'
import WomenBannerShayna from '@/components/WomenBannerShayna.vue'
import InstaShayna from '@/components/InstaShayna.vue'
import PartnerLogoShayna from '@/components/PartnerLogoShayna.vue'
import FooterShayna from '@/components/FooterShayna.vue'
export default {
  name: 'HomeView',
  components: {
    HeaderShayna,
    CarouselShayna,
    WomenBannerShayna,
    InstaShayna,
    PartnerLogoShayna,
    FooterShayna
}
}
</script>
