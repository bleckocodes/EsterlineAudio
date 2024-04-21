<template>
<section class="w-fill mx-auto h-200 flex flex-row items-center bg-image pt-32 pb-16 bg-image px-8 ">
    <!-- Image container with background -->

      <div class="mr-4 w-full text-center sm:w-1/2 sm:text-left bg-black px-5 py-5 rounded-md bg-opacity-75 text-opacity-0">
        <h1 class="mb-6 text-3xl font-bold leading-tight text-white md:text-4xl">
          Welcome to Esterline Audio!
        </h1>
        <p class="mb-2 leading-relaxed text-gray-300">
          This is my website to showcase my previous work & offer my services. I've been in the audio industry for 3 years now and have a degree in Audio Production from Northwest University where I worked on many professional level projects to hone my skills in the industry.
        </p>
        <ul class="mb-8 flex flex-col items-center space-y-1 text-gray-300 sm:items-start">
            <li class="flex items-end">
              <svg
                preserveAspectRatio="xMidYMid meet"
                viewBox="0 0 24 24"
                width="1.2em"
                height="1.2em"
                class="mr-2 text-verdun-green-300"
              >
                <path
                  fill="none"
                  stroke="currentColor" 
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="m5 12l5 5L20 7"
                ></path>
              </svg>
              <span>Various types of coffee beans</span>
            </li>
            <li class="flex items-end">
              <svg
                preserveAspectRatio="xMidYMid meet"
                viewBox="0 0 24 24"
                width="1.2em"
                height="1.2em"
                class="mr-2 text-verdun-green-300"
              >
                <path
                  fill="none"
                  stroke="currentColor"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="m5 12l5 5L20 7"
                ></path>
              </svg>
              <span>Coworking area</span>
            </li>
            <li class="flex items-end">
              <svg
                preserveAspectRatio="xMidYMid meet"
                viewBox="0 0 24 24"
                width="1.2em"
                height="1.2em"
                class="mr-2 text-verdun-green-300"
              >
                <path
                  fill="none"
                  stroke="currentColor"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="m5 12l5 5L20 7"
                ></path>
              </svg>
              <span>Meeting room</span>
            </li>
          </ul>
          <div class="flex flex-col space-y-3 md:flex-row md:space-x-2 md:space-y-0">
            <button
              class="rounded-lg border-0 bg-verdun-green-900 px-6 py-3 text-base text-white shadow-lg transition hover:bg-verdun-green-300 hover:text-gray-900"
            >
              Open menu
            </button>
            <nuxt-link to="/services">
              <button
                class="rounded-lg border-0 bg-white px-6 py-3 text-base text-verdun-green-900 shadow-lg transition hover:bg-verdun-green-300 hover:text-gray-900"
              >
                Explore services
              </button>
            </nuxt-link>
          </div>
      </div>
    <!-- Text container -->
    
    </section>
</template>

<style scoped>
  body {
    background-color: #1f2937; /* Dark background color */
  }
  .bg-image {
    background-image: url('@/components/images/bridge.jpg');
    background-size: cover;
    background-position: center;
  }
</style>