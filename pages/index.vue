<template class="min-h-screen bg-gray-800">
  <div class="min-h-screen bg-gray-800">
    <Hero />
    <div class="text-center text-white">
      <div class="text-5xl font-bold pt-36"></div>
    </div>
    <!--Start Content-->

    <section class="flex flex-col items-center sm:mx-36 pl-10 pb-36 drop-shadow-2xl sm:bg-slate-700 rounded-[64px] sm:flex-row-reverse">
        <div class="w-full h-128 sm:w-1/2 sm:h-auto sm:pl-8">
          <div class=" sm:rounded-r-[64px] overflow-hidden">
            <img
              alt="Security"
              class="object-cover sm:rounded-r-[64px] w-full h-full"
              src="@/components/images/PhotoWorking.jpg"
            />
          </div>
        </div>
        <div class="mr-4 w-full text-center sm:w-1/2 sm:text-left">
          <h2 class="mb-4 text-3xl font-bold leading-tight text-verdun-green-300 md:text-4xl">Industry Experience</h2>
          <p class="leading-relaxed text-slate-300 text-lg">
            My education in Audio Production from Northwest University and three years of experience has prepared me to be a professional engineer in live sound and music industry production projects. I am skilled at providing sound editing, mixing, sound design, production audio, and live audio. I am proficient in recording equipment and software, understand acoustic theory, and can mix tracks. My experience in live sound recording in studios and ability to produce live audio events on stage at venues equips me to benefit you, as I can produce audio works with professional quality sound. Your project will receive my full attention and commitment.
          </p>
          <a
            class="group relative mx-auto text-xl mt-8 inline-block font-semibold underline decoration-verdun-green-300 decoration-2 underline-offset-8 transition text-slate-200 hover:decoration-slate-200 sm:mx-0"
            href="/MyWork"
          >
            View My Work
            <svg
              preserveAspectRatio="xMidYMid meet"
              viewBox="0 0 24 24"
              width="1.2em"
              height="1.2em"
              class="absolute bottom-0 -right-6 scale-x-0 transition group-hover:scale-x-100"
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
        </div>
    </section>

    <section class="flex flex-col items-center sm:mx-36 pr-10 m-20 drop-shadow-2xl sm:bg-slate-700 rounded-[64px] sm:flex-row">
      <div class="rounded-md overflow-hidden w-full h-128 sm:w-1/2 sm:h-auto sm:pr-8">
        <img
          alt="Security"
          class="object-cover sm:rounded-l-[64px] w-full h-full"
          src="@/components/images/Personal.jpg"
        />
      </div>
      <div class="mr-4 w-full text-center sm:w-1/2 sm:text-left">
        <h2 class="mb-4 text-3xl font-bold leading-tight text-verdun-green-300 md:text-4xl">Personalized Service for Projects</h2>
        <p class="leading-relaxed text-slate-300">
          I am a fresh face in the audio world, building my portfolio serving clients. I am full of ideas to implement and ready to bring your ideas to fruition. Together we can make your music sound the way you desire and the way it is meant to be heard! There’s nothing stopping us!         </p>
        <a
          class="group relative mx-auto text-xl mt-8 inline-block font-semibold underline decoration-verdun-green-300 decoration-2 underline-offset-8 transition text-slate-200 hover:decoration-slate-200 sm:mx-0"
          href="/Services"
        >
          My Services
          <svg
            preserveAspectRatio="xMidYMid meet"
            viewBox="0 0 24 24"
            width="1.2em"
            height="1.2em"
            class="absolute bottom-0 -right-6 scale-x-0 transition group-hover:scale-x-100"
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
      </div>
    </section>

    <section class="flex flex-col items-center sm:mx-36 pl-10 m-20 drop-shadow-2xl sm:bg-slate-700 rounded-[64px]  sm:flex-row-reverse">
      <div class="rounded-md overflow-hidden w-full h-128 sm:w-1/2 sm:h-auto sm:pl-8">
        <img
          alt="Security"
          class="object-cover sm:rounded-r-[64px] w-full h-full"
          src="@/components/images/band.png"
        />
      </div>
      <div class="mr-4 w-full text-center sm:w-1/2 sm:text-left">
        <h2 class="mb-4 text-3xl font-bold leading-tight text-verdun-green-300 md:text-4xl">I'm Passionate About Music</h2>
        <p class="leading-relaxed text-slate-300">
          I love making music! As a musician, I have played in various bands and ensembles. I have an ear for sound and persist until it is perfect. I will apply this attention to detail to all my client’s work as well.  
        </p>
        <a
          class="group relative mx-auto mt-8 text-xl inline-block font-semibold underline decoration-verdun-green-300 decoration-2 underline-offset-8 transition  text-slate-200 hover:decoration-slate-200 sm:mx-0"
          href="/About"
        >
          About Me
          <svg
            preserveAspectRatio="xMidYMid meet"
            viewBox="0 0 24 24"
            width="1.2em"
            height="1.2em"
            class="absolute bottom-0 -right-6 scale-x-0 transition group-hover:scale-x-100"
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
      </div>
    </section>
  </div>
</template>


