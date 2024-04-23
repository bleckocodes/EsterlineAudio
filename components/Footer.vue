<template>
   <!-- Top Vertical spacing -->
  
   <footer class="bg-gray-900 flex flex-col items-center text-center text-white p-5">
      
    <div class=" bg-gray-900 "></div>
              <div class="container p-4 pb-0">
                <!--page footer nav-->
                <ul class="flex flex-row justify-center space-x-2 pb-16">
                  <li class="group relative">
                    <nuxt-link 
                      class="block whitespace-nowrap px-3 py-2 text-lg font-bold text-slate-400 no-underline transition hover:text-slate-50" 
                      to="/">
                      Home
                    </nuxt-link>
                  </li>
                  <li class="group relative">
                    <a 
                      class="block whitespace-nowrap px-3 py-2 text-lg font-bold text-slate-400 no-underline transition hover:text-slate-50" 
                      href="/MyWork">
                      My Work
                    </a>
                  </li>
                  <li class="group relative">
                    <a
                      class="block whitespace-nowrap px-3 py-2 text-lg font-bold text-slate-400 no-underline transition hover:text-slate-50" 
                      href="/Services">
                      Services
                  </a>
                  </li>
                  <li class="group relative">
                    <a 
                      class="block whitespace-nowrap px-3 py-2 text-lg font-bold text-slate-400 no-underline transition hover:text-slate-50" 
                      href="/About">
                      About
                    </a>
                  </li>
                  <li class="group relative">
                    <nuxt-link 
                      class="block whitespace-nowrap px-3 py-2 text-lg font-bold text-slate-400 no-underline transition hover:text-slate-50" 
                      to="Contact">
                      Contact
                    </nuxt-link>
                  </li>
                </ul>
            </div>

    
    <!-- Grid container -->
      <div class="container p-4 pb-0">
        <!-- Section: Social media -->
        <section class="mb-4 flex justify-center">
  
          <!-- Instagram -->
          <a class="social-icon" href="https://www.instagram.com/esterline_audio/">
            <i class="fab fa-instagram"></i>
          </a>
  
          <!-- Linkedin -->
          <a class="social-icon" href="https://www.linkedin.com/in/isaiah-esterline-8683b8227/">
            <i class="fab fa-linkedin-in"></i>
          </a>
  
          <!-- Spotify -->
          <a class="social-icon" href="https://open.spotify.com/artist/2ojRNU6OcociN3jZrhkL0D?si=g15Mfo6YRLa9uZnI6gegpQ">
            <i class="fab fa-spotify"></i>
          </a>

          <!-- Youtube -->
          <a class="social-icon" href="https://www.youtube.com/@spunkwaterlake-np2ee">
            <i class="fab fa-youtube"></i>
          </a>
        </section>
        <!-- Section: Social media -->
      </div>
      <!-- Grid container -->
  
      <!-- Bottom Vertical spacing -->
      <div class="my-20"></div>
  
      <!-- Copyright -->
      <div class="text-center pb-16 justify-end">
        © 2024 Copyright:
        <a class="text-white" href="https://mdbootstrap.com/">Esterline Audio</a>
      </div>
      <!-- Copyright -->
    </footer>
  </template>
  
  <style>
  /* Bootstrap Styles */
  .btn-outline-light {
    color: #4F8A10;
    border-color: #4F8A10;
  }
  
  .btn-outline-light:hover {
    color: #fff;
    background-color: #4F8A10;
    border-color: #4F8A10;
  }
  
  .btn-floating {
    box-shadow: none;
  }
  
  /* Social Media Icons */
  .social-icon {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    width: 5%; /* Adjust as needed */
    height: auto; /* Maintain aspect ratio */
    margin: 0 5px; /* Add spacing between icons */
    font-size: 28px; /* Adjust size as needed */
    color: #94a3b8; /* slate-400 color */
    
  }

  .social-icon:hover {
  color: #d2d6dc; /* slate-50 color */
}
  
  /* Add vertical spacing */
  .my-4 {
    margin-top: 1rem; /* Adjust as needed */
    margin-bottom: 1rem; /* Adjust as needed */
  }
  
  /* Font Awesome Styles */
  @import "~@fortawesome/fontawesome-free/css/all.css";
  </style>
  