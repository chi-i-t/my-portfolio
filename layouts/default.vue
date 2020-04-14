<template>
  <div class="container">
    <HeaderSection />
    <div class="main-container">
      <nuxt />
    </div>
    <FooterSection />
  </div>
</template>

<script>
import HeaderSection from "~/components/Header.vue";
import FooterSection from "~/components/Footer.vue";

export default {
  components: {
    HeaderSection,
    FooterSection
  }
};
</script>