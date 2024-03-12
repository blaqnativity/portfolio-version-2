<template>
  <section
    class="grid items-center justify-items-center p-6 shadow-md h-screen"
  >
    <form @submit.prevent class="space-y-10 w-[100%]">
      <div class="title">
        <p class="pText">Contact</p>
        <h1 class="headerText2 text-left md:text-start">Get in touch</h1>
      </div>
      <div class="flex flex-col">
        <label class="pText">Name:</label>
        <input type="text" />
      </div>
      <div class="flex flex-col">
        <label class="pText">Email:</label>
        <input type="email" />
      </div>

      <div class="flex flex-col">
        <label class="pText">Your message</label>
        <textarea name="" id="" cols="30"></textarea>
      </div>

      <button class="mainBtn flex items-center gap-2">
        <span>Send message</span
        ><span class="material-symbols-outlined"> send </span>
      </button>
    </form>
  </section>
</template>

<script>
export default {};
</script>

<style></style>
