<template>
  <section class="grid items-center justify-items-center mb-4 h-dsh">
    <form
      @submit.prevent="handleSubmit"
      class="mt-10 space-y-10 w-[100%] md:w-[50%] bg-white p-8 rounded-md shadow-md"
    >
      <div v-if="errorMessage" class="error">{{ errorMessage }}</div>
      <div class="title">
        <h1 class="headerText2 text-left md:text-start">Get in touch</h1>
      </div>

      <div class="flex flex-col">
        <label class="pText">Email:</label>
        <input type="email" placeholder="enter valid email" v-model="email" />
      </div>

      <div class="grid gap-3">
        <label class="pText">What kind of service do you require of me?</label>
        <select v-model="role" class="w-[70%] p-3 outline-none">
          <option value="Developer">Frontend Developer</option>
          <option value="Wordpress">Wordpress Development</option>
        </select>
      </div>

      <div class="flex flex-col">
        <label class="pText">Your message</label>
        <textarea
          v-model="message"
          placeholder="Your message"
          cols="30"
          rows="2"
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
  erroMessage: false,
  data() {
    return {
      name: "",
      email: "",
      message: "",
      role: "",
      errorMessage: "",
    };
  },
  methods: {
    handleSubmit() {
      if (this.name === "" && this.message === "" && this.role === "") {
        this.errorMessage =
          "All input feilds are required to better communicate what you need my services for!!!";
      }
    },
  },
};
</script>

<style></style>
