<template>
  <section class="grid items-center justify-items-center p-6 shadow-md h-dvh">
    <form
      @submit.prevent
      class="space-y-10 w-[100%] md:w-[50%] bg-white p-8 rounded-md shadow-md"
    >
      <div class="title">
        <p class="pText">Contact</p>
        <h1 class="headerText2 text-left md:text-start">Get in touch</h1>
      </div>
      <div class="flex flex-col">
        <label class="pText">Name:</label>
        <input
          type="text"
          name="name"
          placeholder="Enter first and last name"
          required
        />
      </div>
      <div class="flex flex-col">
        <label class="pText">Email:</label>
        <input
          type="email"
          placeholder="Enter a valid email"
          name="email"
          required
        />
      </div>

      <div class="flex flex-col">
        <label class="pText">Your message</label>
        <textarea
          name="message"
          placeholder="Enter your message"
          cols="30"
          rows="4"
        ></textarea>
      </div>

      <button class="mainBtn flex items-center gap-2">
        <span>Send message</span
        ><span class="material-symbols-outlined"> send </span>
      </button>
    </form>
  </section>
</template>

<script>
export default {
  data() {
    return {};
  },
};
</script>

<style></style>
