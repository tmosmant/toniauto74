<template>
  <div>
    <NavigationBar />
    <HeroSection />
    <GoogleMapSection />
    <FeatureSection />
    <TestimonialSection />
    <ContactSection />
    <BottomBar />
  </div>
</template>

<script setup>
useHead({
  title: "Toni Auto - Garage à Annemasse",
});
</script>

<style>
html {
  scroll-behavior: smooth;
}
</style>
