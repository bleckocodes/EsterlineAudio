<template>
  <section class="w-fill mx-auto flex flex-col sm:flex-row h-200 items-center bg-image pt-36 pb-20 bg-image px-8">
    <!-- Image container with background -->
    <div class="mr-4 w-fit h-inherit text-left sm:w-1/2 bg-black px-5 py-5 rounded-md bg-opacity-75 text-opacity-0">
      <h1 class="mb-6 text-3xl font-bold leading-tight text-white md:text-4xl">
        Welcome to Esterline Audio!
      </h1>
      <p class="mb-2 leading-relaxed text-gray-300">
        This is my website to showcase my previous work & offer my services. I've been in the audio industry for 3 years now and have a degree in Audio Production from Northwest University where I worked on many professional level projects to hone my skills in the industry.
      </p>
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
    <!-- Logo Image -->
    <img
      class="object-cover object-center w-full mr-4 filter-green"
      src="@/components/images/EAPSFullW.png"
      alt="Logo"
      height="64"
      style="max-width: 500px; max-height: 500px;"
    />
  </section>
</template>

<style scoped>
.bg-image {
  background-image: url(@/components/images/Personal.jpg);
  background-position: 0% 20%; /* Positioning the image */
  background-repeat: no-repeat;
  background-size: cover;
  filter: grayscale(100%)
}
.filter-green {
  filter: brightness(150%) saturate(100%) hue-rotate(120deg); /* Adjust the filter as needed */
}
</style>