<template>
  <!-- ==============Navbar Section=============== -->
  <nav class="relative p-6 flex justify-between items-center z-20">
    <div class="flex items-center">
      <NuxtLink to="/" class="logo">{{ logo }}</NuxtLink>
      <!-- <button class="logo">{{ logo }}</button> -->
    </div>

    <!-- nav menu -->
    <!-- <ul class="main_menu hidden space-x-10 md:flex items-center">
      <li v-for="link in links" :key="link.url">
        <NuxtLink :to="link.url">{{ link.text }}</NuxtLink>
      </li>
    </ul> -->

    <!-- download resume link -->
    <a href="assets" class="mainBtn" download="olukayode.pdf"
      >Download my resume</a
    >

    <div class="block md:hidden" @click="toggleBtn">
      <span class="material-symbols-outlined" v-if="showMenu">
        close_small
      </span>
      <span class="material-symbols-outlined" v-else> menu </span>
    </div>

    <!-- <div class="dropdown_menu" v-if="showMenu">
      <ul class="main_menu space-x-10 md:flex">
        <li v-for="link in links" :key="link.url">
          <NuxtLink :to="link.url">{{ link.text }}</NuxtLink>
        </li>
      </ul>
    </div> -->
  </nav>
</template>

<script>
export default {
  data() {
    return {
      showMenu: false,
      logo: "Olukayode_",
      links: [
        { text: "Portfolio", url: "/" },
        { text: "Contact", url: "/" },
      ],
    };
  },
  methods: {
    toggleBtn() {
      this.showMenu = !this.showMenu;
    },
  },
};
</script>

<style></style>
