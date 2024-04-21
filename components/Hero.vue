<template>
  <section class="container mx-auto flex flex-col items-center px-8 pb-36 sm:flex-row-reverse sm:px-12">
    <div class="relative mb-8 w-full sm:mb-0 sm:w-1/2 sm:pl-4 md:pl-16">
      <img
        alt="Background Image"
        class="absolute inset-0 w-full h-full object-cover"
        src="@/components/images/Trees.png" <!-- Corrected image path -->
      />
      <img
        alt="EAPSFullW"
        class="relative z-10 w-full h-full object-cover"
        src="@/components/images/EAPSFullW.png" <!-- Corrected image path -->
      />
    </div>
    <div class="mr-4 w-full text-center sm:w-1/2 sm:text-left">
      <h1 class="mb-6 text-3xl font-bold leading-tight text-white md:text-4xl">
        Welcome to Esterline Audio!
      </h1>
      <p class="mb-2 leading-relaxed text-gray-300">
        This is my website to showcase my previous work & offer my services. I've been in the audio industry for 3 years now and have a degree in Audio Production from Northwest University where I worked on many professional level projects to hone my skills in the industry.
      </p>
      <ul class="mb-8 flex flex-col items-center space-y-1 text-gray-300 sm:items-start">
        <!-- List items remain unchanged -->
      </ul>
      <div class="flex flex-col space-y-3 md:flex-row md:space-x-2 md:space-y-0">
        <!-- Buttons remain unchanged -->
      </div>
    </div>
  </section>
</template>

<style scoped>
  body {
    background-color: #1f2937; /* Dark background color */
  }
</style>