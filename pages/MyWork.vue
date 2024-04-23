<template>
    <div class="min-h-screen bg-gray-800">
      <div class="bg-gray-800 text-center text-white">
        <div class="text-5xl font-bold pt-10 pb-10">My Work</div>
      </div>
      <div class="text-center text-white text-2xl font-semibold pt-10 pb-10">
        To showcase my work, please click the links to my YouTube videos, Instagram posts, and Spotify song lists.
      </div>
        <div class="container p-4 pb-10">
            <!-- Section: Social media -->
            <section class="mb-4 flex justify-center">
                <!-- Instagram large -->
                <a class="social-icon instagram extra-large px-24" href="https://www.instagram.com/esterline_audio/">
                    <i class="fab fa-instagram"></i>
                </a>

                <!-- Linkedin large-->
                <a class="social-icon linkedin extra-large px-24" href="https://www.linkedin.com/in/isaiah-esterline-8683b8227/">
                    <i class="fab fa-linkedin-in"></i>
                </a>

                <!-- Spotify large-->
                <a class="social-icon spotify extra-large px-24" href="https://open.spotify.com/artist/2ojRNU6OcociN3jZrhkL0D?si=g15Mfo6YRLa9uZnI6gegpQ">
                    <i class="fab fa-spotify"></i>
                </a>

                <!-- Youtube large-->
                <a class="social-icon youtube extra-large px-24" href="https://www.youtube.com/@spunkwaterlake-np2ee">
                    <i class="fab fa-youtube"></i>
                </a>
            </section>
            <!-- Section: Social media -->
        </div>
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 flex pb-36 items-center flex-col ">
        <!-- Embedded YouTube Video -->
        <div class="mb-8">
          <iframe width="560" height="315" src="https://www.youtube.com/embed/rxJjjyezZEE" frameborder="0" allowfullscreen></iframe>
        </div>
        
        <!--Embedded YouTube Video-->
        <div>
          <iframe width="560" height="315" src="https://www.youtube.com/embed/Bq2dYxushZY" frameborder="0" allowfullscreen></iframe>
        </div>

        <!--Audio File-->
        <p class="pt-16 pb-6 font-bold text-white">Dark Wave</p>
        <audio controls controlsList="nodownload">
            <source src="@/components/audio/Darkwave 1.wav" type="audio/wav">
            Your browser does not support the audio element.
        </audio>

        <!--Audio File-->
        <p class="pt-16 pb-6 font-bold text-white">Escaping West</p>
        <audio controls controlsList="nodownload">
            <source src="@/components/audio/DolbyA.escapingwest_11.29.23.mp3" type="audio/mp3">
            Your browser does not support the audio element.
        </audio>

        <!--Audio File-->
        <p class="pt-16 pb-6 font-bold text-white">Heffalump Rise</p>
        <audio controls controlsList="nodownload">
            <source src="@/components/audio/Heffalump Rise 1.wav" type="audio/wav">
            Your browser does not support the audio element.
        </audio>

        <!--Audio File-->
        <p class="pt-16 pb-6 font-bold text-white">In My Bones</p>
        <audio controls controlsList="nodownload">
            <source src="@/components/audio/In My Bones DEC 8.mp3" type="audio/mp3">
            Your browser does not support the audio element.
        </audio>

       
        <!--Audio File-->
        <p class="pt-16 pb-6 font-bold text-white">Lead Acetate</p>
        <audio controls controlsList="nodownload">
            <source src="@/components/audio/Lead Acetate Final.wav" type="audio/wav">
            Your browser does not support the audio element.
        </audio>


        <!--Audio File-->
        <p class="pt-16 pb-6 font-bold text-white">Mood Music</p>
        <audio controls controlsList="nodownload">
            <source src="@/components/audio/Mood Music 1.wav" type="audio/wav">
            Your browser does not support the audio element.
        </audio>

        <!--Audio File-->
        <p class="pt-16 pb-6 font-bold text-white">Own Way to Boogie</p>
        <audio controls controlsList="nodownload">
            <source src="@/components/audio/OwnWayToBoogie_StereoMix_1.wav" type="audio/wav">
            Your browser does not support the audio element.
        </audio>

        <!--Audio File-->
        <p class="pt-16 pb-6 font-bold text-white">Peaches</p>
        <audio controls controlsList="nodownload">
            <source src="@/components/audio/Peaches 2.wav" type="audio/wav">
            Your browser does not support the audio element.
        </audio>

        <!--Audio File-->
        <p class="pt-16 pb-6 font-bold text-white">Perfume</p>
        <audio controls controlsList="nodownload">
            <source src="@/components/audio/Perfume Add.wav" type="audio/wav">
            Your browser does not support the audio element.
        </audio>

        <!--Audio File-->
        <p class="pt-16 pb-6 font-bold text-white">Poor Tom</p>
        <audio controls controlsList="nodownload">
            <source src="@/components/audio/Poor Tom .wav" type="audio/wav">
            Your browser does not support the audio element.
        </audio>

      </div>
    </div>
  </template>



<style>
.social-icon.large {
  font-size: 69px; /* Adjust size for large icons */
  color: #8AB661; /* Verdun-green color */
}

.social-icon.medium {
  font-size: 69px; /* Adjust size for medium icons */
  color: #8AB661; /* Change color for medium icons */
}

.social-icon.small {
  font-size: 69px; /* Adjust size for small icons */
  color: #8AB661; /* Change color for small icons */
}

.social-icon.extra-large {
  font-size: 69px; /* Adjust size for extra large icons */
  color: #8AB661; /* Change color for extra large icons */
}


</style>