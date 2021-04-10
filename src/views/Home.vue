<template>
  <div class="home">
    <HeaderShayna />
    <HeroShayna />
    <WomenBanner />
    <Instagram />
    <PartnerLogo />
    <FooterShayna />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";

import HeaderShayna from "@/components/HeaderShayna.vue";
import HeroShayna from "@/components/HeroShayna.vue";
import WomenBanner from "@/components/WomenBanner.vue";
import Instagram from "@/components/Instagram.vue";
import PartnerLogo from "@/components/PartnerLogo.vue";
import FooterShayna from "@/components/FooterShayna.vue";

export default {
  name: "Home",
  components: {
    HeaderShayna,
    HeroShayna,
    WomenBanner,
    Instagram,
    PartnerLogo,
    FooterShayna,
  },
};
</script>
