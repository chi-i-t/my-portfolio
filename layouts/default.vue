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
import HeaderSection from "~/components/header.vue";
import FooterSection from "~/components/footer.vue";

export default {
  components: {
    HeaderSection,
    FooterSection
  }
};
</script>