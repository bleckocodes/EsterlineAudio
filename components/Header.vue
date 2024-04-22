<template>
  <div class="height-auto bg-verdun-green-400 text-base text-white">
    <header class="bg-verdun-green-400 text-white mx-auto flex w-full items-center justify-between py-4 px-6">
      <nuxt-link to="/">
        <div class="w-full text-center text-lg font-bold sm:w-fit sm:text-left">
          <span class="text-40 white-500">Esterline Audio Production Services</span>
        </div>
      </nuxt-link>

      <nav class="hidden text-base sm:block">
  <ul class="flex items-center space-x-2">
    <li class="group relative">
      <nuxt-link 
        class="block whitespace-nowrap px-3 py-2 text-lg font-semibold text-slate-900 no-underline transition hover:text-slate-400 dark:hover:text-slate-50" 
        to="/">
        Home
      </nuxt-link>
    </li>
    <li class="group relative">
      <nuxt-link 
        class="block whitespace-nowrap px-3 py-2 text-lg font-semibold text-slate-900 no-underline transition hover:text-slate-400 dark:hover:text-slate-50" 
        to="MyWork">
        My Work
      </nuxt-link>
    </li>
    <li class="group relative">
      <a
        class="block whitespace-nowrap px-3 py-2 text-lg font-semibold text-slate-900 no-underline transition hover:text-slate-400 dark:hover:text-slate-50" 
        href="/Services">
        Services
    </a>
    </li>
    <li class="group relative">
      <a 
        class="block whitespace-nowrap px-3 py-2 text-lg font-semibold text-slate-900 no-underline transition hover:text-slate-400 dark:hover:text-slate-50" 
        href="/About">
        About
      </a>
    </li>
    <li class="group relative">
      <nuxt-link 
        class="block whitespace-nowrap px-3 py-2 text-lg font-semibold text-slate-900 no-underline transition hover:text-slate-400 dark:hover:text-slate-50" 
        to="Contact">
        Contact
      </nuxt-link>
    </li>
  </ul>
</nav>

      <button
        class="block text-slate-900 hover:text-slate-400 dark:hover:text-slate-50 sm:hidden"
        title="Open navigation menu"
      >
        <svg
          preserveAspectRatio="xMidYMid meet"
          viewBox="0 0 24 24"
          width="1.2em"
          height="1.2em"
        >
          <path
            fill="none"
            stroke="currentColor"
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M4 6h16M4 12h16M4 18h16"
          ></path>
        </svg>
      </button>

      <nav
        class="fixed -right-1/2 top-0 z-20 h-full w-1/2 transform overflow-y-auto bg-white py-4 text-base transition dark:bg-slate-900 sm:hidden"
      >
        <ul class="flex flex-col space-y-2">
          <li class="text-right">
            <button
              class="px-6 py-2 text-slate-900 hover:text-slate-400 dark:hover:text-slate-50"
            >
              <svg
                preserveAspectRatio="xMidYMid meet"
                viewBox="0 0 24 24"
               width="1.2em"
                height="1.2em"
              >
                <path
                  fill="none"
                  stroke="currentColor"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M5 12h14m-4 4l4-4m-4-4l4 4"
                ></path>
              </svg>
            </button>
          </li>
          <li class="group relative w-full overflow-x-visible text-right">
            <nuxt-link
              class="mx-4 block whitespace-nowrap px-3 py-2 text-lg font-semibold text-slate-900 no-underline transition hover:text-slate-400 dark:hover:text-slate-50"
              to="/"
            >
              Home
            </nuxt-link>
          </li>
        </ul>
      </nav>
    </header>
  </div>
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

  /* Hover effect on navigation links */
  nav ul li a:hover {
    color: #48bb78; /* Change text color on hover */
  }

  /* Hover effect on dropdown menu */
  nav ul li ul li a:hover {
    color: #48bb78; /* Change text color on hover */
  }
</style>
