`<template>
    <div class="bg-gray-800"> 
    <div class="bg-gray-800 text-center text-white">
      <div class="text-5xl font-bold pt-10 pb-10">Services</div>
    </div>
    <!-- Services -->
    <section class="container mx-auto bg-gray-800 px-12 py-28">
      <!-- Heading -->
      <h1
        class="mb-24 w-full text-center text-4xl font-extrabold text-slate-50 sm:mx-auto sm:mb-20 sm:w-4/5"
      >
        <span class="text-verdun-green-300">Multiple Plans</span>
        for Artists & Podcasters
      </h1>
      <!-- Service 1 -->
        <div class="flex w-full flex-col bg-gray-800 justify-between sm:mb-0 sm:w-1/2!">
          <div class="w-full text-center">
            <img
              alt="Service 1"
              class="mx-auto mb-4 w- h-64 rounded image-size-fit invert"
              src="@/components/images/mixing.png"
            />
            <h2
              class="mb-2 text-xl font-bold leading-tight text-verdun-green-300 md:text-xl"
            >
            Single Song Mixing 
            </h2>
            <h3 class="text-gray-500 font-bold">
                $40.00 
            </h3>
            <p class="mt-4 leading-relaxed text-slate-400">
              3-5 minute
              song mix, with a professional sound design.
              <div class="mb-36 leading-relaxed text-slate-400" >
                 Up to 16 channels of audio can be added.</div>
            </p>
          </div>
        </div>

        <!-- Service 2 -->
        <div class="flex w-full flex-col bg-gray-800 justify-between sm:mb-0 sm:w-1/2!">
          <div class="w-full text-center">
            <img
              alt="Service 1"
              class="mx-auto mb-4 w- h-64 rounded image-size-fit invert"
              src="@/components/images/Studio.png"
            />
            <h2
              class="mb-2 text-xl font-bold leading-tight text-verdun-green-300 md:text-xl"
            >
            Extended Play Through Album Mixing 
            </h2>
            <h3 class="text-gray-500 font-bold">
                $50.00 per every three minutes of mixed audio.
            </h3>
            <p class="mt-4 leading-relaxed text-slate-400">
                An extended play (EP) is a musical recording that contains more tracks than a single but fewer than an album.              <div class=" leading-relaxed text-slate-400" >
                 Up to 16 channels of audio per song.</div>
                <div class="mb-36 leading-relaxed text-slate-400" >
                    Anything from ten minutes to an hour of finished product song mix, with a professional sound design.</div>
                 
            </p>
          </div>
        </div>


        <!-- Service 3 -->
        <div class="flex w-full flex-col bg-gray-800 justify-between sm:mb-0 sm:w-1/2!">
          <div class="w-full text-center">
            <img
              alt="Service 1"
              class="mx-auto mb-4 w- h-64 rounded image-size-fit invert"
              src="@/components/images/studio2.png"
            />
            <h2
              class="mb-2 text-xl font-bold leading-tight text-verdun-green-300 md:text-xl"
            >
            Professional Music Studio Time 
            </h2>
            <h3 class="text-gray-500 font-bold">
                $150.00 per hour as well as the rate of the studio. 
            </h3>
            <p class="mt-4 leading-relaxed text-slate-400">
                Recording engineer services include: planning, paperwork, routing,
                <div class="mb-36 leading-relaxed text-slate-400" >
                microphone, placement expertise, etc.</div>
            </p>
          </div>
        </div>


        <!-- Service 4 -->
        <div class="flex w-full flex-col bg-gray-800 justify-between sm:mb-0 sm:w-1/2!">
          <div class="w-full text-center">
            <img
              alt="Service 1"
              class="mx-auto mb-4 w- h-64 rounded image-size-fill invert "
              src="@/components/images/podcast.png"
            />
            <h2
              class="mb-2 text-xl font-bold leading-tight text-verdun-green-300 md:text-xl"
            >
            Podcast Studio Time 
            </h2>
            <h3 class="text-gray-500 font-bold">
                $50.00 per hour
            </h3>
            <p class="mt-4 leading-relaxed text-slate-400">
                My equipment includes:</p>
            <p class=" leading-relaxed text-slate-400">
                Behringer C-1 
            <div class=" leading-relaxed text-slate-400" >
                2 Lavalier microphones</div>
            <div class="mb-36 leading-relaxed text-slate-400" >
                Zoom recorder</div>
            </p>
          </div>
        </div>


        <!-- Service 5 -->
        <div class="flex w-full flex-col bg-gray-800 justify-between sm:mb-0 sm:w-1/2!">
          <div class="w-full text-center">
            <img
              alt="Service 1"
              class="mx-auto mb-4 w- h-64 rounded image-size-fit invert"
              src="@/components/images/mixtable.png"
              
            />
            <h2
              class="mb-2 text-xl font-bold leading-tight text-verdun-green-300 md:text-xl"
            >
            Podcast Editing
            </h2>
            <h3 class="text-gray-500 font-bold">
                $50.00 per episode.
            </h3>
            <p class="mt-4 leading-relaxed text-slate-400">
              3-5 minute
              Thirty to fifty minutes.               
              <div class="mb-36 leading-relaxed text-slate-400" >
                One to three voices</div>
            </p>
          </div>
        </div>
     


        <!-- Heading -->
      <h1
        class="mb-24 w-full text-center text-4xl bg-gray-800 font-extrabold text-slate-50 sm:mx-auto sm:mb-20 sm:w-4/5"
      >
        <span class="text-verdun-green-300">Interested?</span>

      </h1>
      
        <!--Contact me button-->
        <a
  class="contact-me-button group relative mx-auto mt-8 font-semibold underline decoration-verdun-green decoration-2 underline-offset-8 transition text-slate-200 hover:decoration-slate-200 sm:mx-0"
  href="/Contact"
>
    Contact Me
  <svg
    preserveAspectRatio="xMidYMid meet"
    viewBox="0 0 24 24"
    width="4em"
    height="1.2em"
    class="absolute bottom-0 -right-10 scale-x-0 transition group-hover:scale-x-100"
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
</a>


   </section>
    </div>
</template>

<style>
.contact-me-button {
    display: block;
    margin: 0 auto;
    font-size: 1.5em;
    width: 200px;
  }
</style>