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
  script: [
    {
      src: "https://www.googletagmanager.com/gtag/js?id=G-GPB8MQ0YPB",
      async: true,
    },
    {
      innerHTML: `
        window.dataLayer = window.dataLayer || [];
        function gtag(){dataLayer.push(arguments);}
        gtag('js', new Date());

        gtag('config', 'G-GPB8MQ0YPB');
      `,
    },
  ],
});
</script>

<style>
html {
  scroll-behavior: smooth;
}
</style>
