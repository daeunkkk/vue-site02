<template>
 <HeaderSection />
 <SliderSection />
 <ServiceSection />
 <BrandSection />
 <ItemSection />
 <IntroSection />
 <ReviewSection />
 <FooterSection />
</template>

<script>
 import HeaderSection from "./components/HeaderSection.vue";
 import SliderSection from "./components/SliderSection.vue";
 import ServiceSection from "./components/ServiceSection.vue";
 import BrandSection from "./components/BrandSection.vue";
 import ItemSection from "./components/ItemSection.vue";
 import IntroSection from "./components/IntroSection.vue";
 import ReviewSection from "./components/ReviewSection.vue";
 import FooterSection from "./components/FooterSection.vue";

 export default {
  name: "App",
  components: {
    HeaderSection,
    SliderSection,
    ServiceSection,
    BrandSection,
    ItemSection,
    IntroSection,
    ReviewSection,
    FooterSection
  },
};
</script>
 
<style>
@import "./App.css";
</style>
