<template>
  <!-- Hero section start -->
  <section
    id="hero"
    class="p-6 flex items-center justify-center h-[50vhnote] md:h-[80vh]"
  >
    <div class="flex items-center text-center flex-col space-y-6">
      <p class="lead">Hey there, I'm Olukayode Asemudara</p>
      <h1 class="headerText">
        Building digital products, brands and experience
      </h1>

      <NuxtLink to="/ContactView" class="mainBtn uppercase"
        >Hire me now</NuxtLink
      >
    </div>
  </section>
  <!-- Hero section end -->

  <!-- my works display start -->
  <section id="works" class="p-6 flex items-center mt-6">
    <div>
      <div class="space-y-4 md:ml-32">
        <p class="lead">my services...</p>
        <h1 class="headerText2 text-left md:text-start">
          The work I do, and business I help.
        </h1>
      </div>

      <!-- services grid column -->
      <div
        class="grid grid-cols-1 mt-10 gap-4 md:max-w-[80%] md:grid-cols-3 mx-auto bg-[url('assets/img/bg3.png')] bg-cover bg-center bg-no-repeat"
      >
        <!-- info box start -->
        <div class="infoBox md:col-span-2">
          <div class="bg-gray-50 w-fit p-4 rounded-lg">
            <span class="material-symbols-outlined"> code_blocks </span>
          </div>
          <p class="lead">Frontend Development</p>
          <p class="lightText">
            I create responsive websites that allow the user to experience your
            website in the best and most appropriate way suited to the device
            they are using.
          </p>
        </div>
        <!-- info box end -->

        <!-- info box start -->
        <div class="infoBox md:row-span-2">
          <div class="bg-gray-50 w-fit p-4 rounded-lg">
            <span class="material-symbols-outlined"> language </span>
          </div>
          <p class="lead">Wordpress Design</p>
          <p class="lightText">
            Positioning the brand first. I create visual identity across
            platforms. WordPress is the world’s most popular content management
            system which I have many years of experience with.
          </p>
        </div>
        <!-- info box end -->

        <!-- info box start -->
        <div class="infoBox md:col-span-2">
          <div class="bg-gray-50 w-fit p-4 rounded-lg">
            <span class="material-symbols-outlined"> support_agent </span>
          </div>
          <p class="lead">Technical Support</p>
          <p class="lightText">
            If you’d like to find out more about how I work and my process of
            working with clients, please send me a message in the contact page
            and give a little information about the project you have in mind.
          </p>
        </div>
        <!-- info box end -->
      </div>
    </div>
  </section>
  <!-- my works display end -->

  <!-- about me start -->
  <section id="about" class="p-6 flex items-center mt-32">
    <div
      class="grid grid-cols-1 md:grid-cols-3 place-content-center content-center gap-6 mx-auto w-[100%] items-center"
    >
      <!-- text area left -->
      <div class="space-y-6">
        <h1 class="headerText2 text-left md:text-start">A bit about me</h1>
        <p class="pText">
          Olukayode is a Software Engineer, Olukayode has two years experience
          providing front-end development, producing high quality responsive
          websites, cross platform mobile-apps and exceptional user experience.
        </p>
        <p class="pText">
          The work he provides is of highest quality, fully responsive, and
          tested in a wide range of devices. He takes great care to ensure each
          project is well-documented and easily maintainable so you can enhance
          a website as your company grows.
        </p>
      </div>

      <!-- img -->
      <div>
        <img src="/assets/img/about.jpg" alt="" class="rounded-xl" />
      </div>
      <!-- img area end -->

      <!-- text area right -->
      <div class="space-y-4">
        <div class="space-y-6">
          <span class="headerText2">3+</span>
          <p class="lead">Years Of Experience in Wordpress Site Development</p>
        </div>
        <div class="line"></div>
        <div class="space-y-6">
          <span class="headerText2">2+</span>
          <p class="lead">Years of Frontend Design</p>
        </div>

        <div class="line"></div>
        <div class="space-y-6">
          <span class="headerText2">3</span>
          <p class="lead">Portfolios out there...</p>
        </div>
      </div>
    </div>
  </section>
  <!-- about me end -->

  <!-- ================Skills Section=============== -->
  <section class="mt-32 mb-10">
    <div class="container mx-auto px-6 space-y-6">
      <div class="flex flex-col space-y-4 items-center">
        <h4 class="lead">Skills</h4>
        <h2 class="headerText2">Tech Stack.</h2>
        <p class="lead">
          I have experience working with the following technologies
        </p>
      </div>

      <div class="flex flex-wrap items-center justify-center gap-6">
        <span class="pill">HTML</span>
        <span class="pill">CSS</span>
        <span class="pill">Javascript (ES6)</span>
        <span class="pill">Vue-JS</span>
        <span class="pill">NUXT-3</span>
        <span class="pill">Tailwindcss</span>
        <span class="pill">Bootstrapcss</span>
        <span class="pill">Figma</span>
        <span class="pill">Adobe XD</span>
        <span class="pill">Canva Design</span>
        <span class="pill">Webflow</span>
        <span class="pill">Wordpress</span>
        <span class="pill">Netlify</span>
        <span class="pill">Git</span>
      </div>
    </div>
  </section>

  <!-- footer section -->
  <section
    id="footer"
    class="mt-32 rounded-xl p-6 grid items-start md:items-center w-[100%] h-[30vh] md:h-[50vh] bg-gray-900"
  >
    <div class="space-y-10">
      <h1 class="headerText2White md:text-start">Have an idea?</h1>
      <h1 class="headerText2White md:text-start flex items-center">
        Let's talk <span class="material-symbols-outlined"> north_east </span>
      </h1>
    </div>

    <!-- footer links -->
    <div class="grid grid-cols-1 md:grid-cols-2 justify-center items-center">
      <div class="flex gap-2 items-center text-white">
        <span class="material-symbols-outlined"> contact_mail </span>
        <h3 class="">theolukayodeasemudara@gmail.com</h3>
      </div>
    </div>
  </section>
</template>
