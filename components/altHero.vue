<template>
  <section class="relative container mx-auto flex flex-col px-8 py-36 sm:flex-row-reverse sm:px-12">
    <!-- Background image -->
    <div class="absolute inset-0 z-0 bg-cover bg-center" :style="'background-image: url(\'./images/Trees.png\');'"></div>

    <!-- Logo image -->
    <img
      alt="Logo"
      class="mb-8 w-full dark:contrast-200 sm:mb-0 sm:mr-4 sm:w-1/2 z-10"
      :src="require('')"
    />

    <div class="mr-4 w-full text-center sm:w-1/2 sm:text-left z-10">
      <h1 class="mb-4 text-3xl font-bold leading-tight dark:text-gray-100 md:text-4xl">
        Train your mind,
        <br />
        be peaceful
      </h1>
      <p class="mb-8 leading-relaxed text-slate-700 dark:text-gray-300">
        Our sanctuary is a good place to learn meditation, yoga and meet people
        with positive vibes.
      </p>
      <button class="rounded-lg border-0 bg-verdun-green-500 px-12 py-2 text-base text-white shadow-lg shadow-verdun-green-900 dark:shadow-verdun-green-700 dark:hover:shadow-verdun-green-400 transition hover:bg-verdun-green-600 hover:shadow-verdun-green-600">
        Register now
      </button>
    </div>
  </section>
</template>

<style>
  body.dark {
    background-color: #1f2937; /* Adjust as needed */
  }

  /* Adjust dark mode text color */
  @media (prefers-color-scheme: dark) {
    .dark\:text-gray-100 {
      color: #f3f4f6; /* Adjust as needed */
    }

    .dark\:text-gray-300 {
      color: #d1d5db; /* Adjust as needed */
    }
  }
</style>
