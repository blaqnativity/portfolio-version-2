<template>
  <!-- ==============Navbar Section=============== -->
  <section id="navbar" class="w-[100%]">
    <nav class="flex justify-between items-center p-6 w-[100%]">
      <NuxtLink to="/" class="logo">{{ logo }}</NuxtLink>

      <!-- download resume link -->
      <a
        href="assets/olukayode.pdf"
        class="mainBtn"
        download="olukayode's resume"
        >Download CV</a
      >
    </nav>
  </section>
</template>

<script>
export default {
  data() {
    return {
      logo: "Olukayode_",
    };
  },
};
</script>

<style></style>
