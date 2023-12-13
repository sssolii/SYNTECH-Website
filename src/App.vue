<script setup lang="ts">
import customHeader from "./components/Header.vue";
import customFooter from "./components/Footer.vue";
import customBanner from "./components/Banner.vue";
import customCarousel from "./components/Carousel.vue";
</script>

<template>
  <customHeader />
  <customBanner />
  <div class="container">
    <h1 class="is-size-1 has-text-weight-bold" style="color: #002661">
      ONGOING EVENTS
    </h1>
  </div>
  <div style="height: 25px"></div>
  <customCarousel />

  <customFooter />
</template>
