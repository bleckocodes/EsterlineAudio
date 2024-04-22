<template>
  <section class="relative w-full mx-auto flex flex-col sm:flex-row items-center">
    <!-- Background Image -->
    <div class="absolute inset-0 bg-image bg-opacity-75"></div>
    <!-- Text Content Column -->
    <div class="relative z-10 w-full sm:w-1/2 pl-16 flex flex-col justify-center bg-black px-5 py-5 rounded-md bg-opacity-75 mt-64"> <!-- Adjust mt-20 for the desired margin top -->
      <h1 class="mb-6 text-3xl font-bold leading-tight text-verdun-green-300 md:text-4xl">
        Welcome to Esterline Audio!
      </h1>
      <p class="mb-2 leading-relaxed text-gray-300">
        At Esterline Audio Production Services, I am focused on personalized service to cater to your specific audio production needs. I’m a fresh face in the audio world, eager to dedicate all my skills and energy to your project. I am excited to apply my audio engineering and artistic design experience to launch your music talent to the next level.  Your project will receive my full attention and commitment. Let’s create something great together!      </p>
      <ul class="mb-8 flex flex-col items-center space-y-1 text-gray-300 sm:items-start">
        <!-- List items here -->
      </ul>
      <div class="flex flex-col space-y-3 md:flex-row md:space-x-2 md:space-y-0">
        <nuxt-link to="/services" class="disabled:opacity-50 disabled:cursor-not-allowed whitespace-nowrap w-full text-center py-2 px-5 font-bolder border-b hover:bg-white hover:text-black text-base font-medium text-white rounded-md focus:outline-none">
          Learn More
        </nuxt-link>
        <nuxt-link to="/contact" class="disabled:opacity-50 disabled:cursor-not-allowed whitespace-nowrap w-full text-center py-2 px-5 font-bolder border-b hover:bg-white hover:text-black text-base font-medium text-white rounded-md focus:outline-none">
          Contact Me
        </nuxt-link>
      </div>
    </div>   
    <!-- Logo Image Column -->
    <div class="relative z-10 w-full sm:w-1/2 flex justify-center items-center">
      <img
        class="object-cover object-center w-full filter-green"
        src="@/components/images/EAPSFullW.png"
        alt="Logo"
        height="64"
        style="max-width: 500px; max-height: 500px;"
      />
    </div>
  </section>
</template>

<style scoped>
.bg-image {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 90vh; /* Adjust height to move the background image further down */
  background-image: url(@/components/images/Personal.jpg);
  background-position: 0% 20%; /* Positioning the image */
  background-repeat: no-repeat;
  background-size: cover;
  /* Apply grayscale filter only to background image */
  filter: grayscale(100%);
}
.filter-green {
  filter: brightness(150%) saturate(100%) hue-rotate(120deg); /* Adjust the filter as needed */
}
</style>