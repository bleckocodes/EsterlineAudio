<template>
  <div class="sticky top-0 bg-verdun-green-400 text-base text-white z-50">
    <header class="mx-auto flex w-full items-center justify-between py-4 px-6">
      <nuxt-link to="/">
        <div class="w-full text-center text-lg font-bold sm:w-fit sm:text-left">
          <img
            class="w-30 h-16 object-cover justify-right"
            src="@/components/images/EAPSTextB.png"
            alt="Logo"
            @mouseover="invertColors"
            @mouseleave="revertColors"
          />
        </div>
      </nuxt-link>

      <nav class="hidden text-base sm:block">
        <ul class="flex items-center space-x-2">
          <li class="group relative">
            <nuxt-link 
              class="block whitespace-nowrap px-3 py-2 text-lg font-bold text-white no-underline transition hover:text-slate-50" 
              to="/">
              Home
            </nuxt-link>
          </li>
          <li class="group relative">
            <nuxt-link 
              class="block whitespace-nowrap px-3 py-2 text-lg font-bold text-white no-underline transition hover:text-slate-50" 
              to="MyWork">
              My Work
            </nuxt-link>
          </li>
          <li class="group relative">
            <a
              class="block whitespace-nowrap px-3 py-2 text-lg font-bold text-white no-underline transition hover:text-slate-50" 
              href="/Services">
              Services
            </a>
          </li>
          <li class="group relative">
            <a 
              class="block whitespace-nowrap px-3 py-2 text-lg font-bold text-white no-underline transition hover:text-slate-50" 
              href="/About">
              About
            </a>
          </li>
          <li class="group relative">
            <nuxt-link 
              class="block whitespace-nowrap px-3 py-2 text-lg font-bold text-white no-underline transition hover:text-slate-50" 
              to="Contact">
              Contact
            </nuxt-link>
          </li>
        </ul>
      </nav>
      <!-- Mobile Menu -->
      <button
        @click="toggleMobileMenu"
        class="block text-white hover:text-slate-50 sm:hidden"
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
    </header>
  </div>
</template>

<script>
export default {
  data() {
    return {
      isMobileMenuOpen: false
    };
  },
  methods: {
    toggleMobileMenu() {
      this.isMobileMenuOpen = !this.isMobileMenuOpen;
    },
    invertColors(event) {
      event.target.style.filter = "invert(100%)";
    },
    revertColors(event) {
      event.target.style.filter = "none";
    }
  },
  computed: {
    isMobile() {
      if (process.client) {
        // Check if screen width is less than 768 pixels (typical mobile breakpoint)
        return window.innerWidth < 768;
      }
      // Default to false for SSR
      return false;
    }
  }
};
</script>

<style>
  /* Add any additional styles here */
</style>