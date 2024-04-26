<template> ``
    <div class="bg-gray-800"> <!-- Update -->
      <div class="sm:mx-36">
        <div class="bg-gray-800 text-center text-white">
          <div class="text-5xl font-bold pt-10 pb-10">Let Me Introduce Myself...</div>
        </div>
        
        <div class="about-me-container bg-gray-800">
          <div class="about-me-content">
            
            <div class="about-me-text mr-12">
              <h2 class="about-me-title font-bold text-verdun-green-300">I'm Isaiah Esterline.</h2>
                <p class="about-me-description text-slate-400 pb-5">
                I found my calling in the world of audio. I am an Audio Engineer, currently based in Kirkland, Washington, with a passion for music and sound. My journey into audio engineering began with a love for music and a curiosity about how it is created.
                </p>
                <p class="about-me-description text-slate-400 pb-5">
                I am finishing my major in Audio Production at Northwest University, and my education has prepared me to be an engineer in live sound and music industry production. I have three years of experience and I am honing my skills and deepening my understanding. I am proficient in sound editing, mixing, sound design, production audio, and live audio. With hands-on experience in recording equipment and software, coupled with a solid grasp of acoustic theory and track mixing, I am equipped to deliver professional-grade audio works. Whether it is recording in the studio or producing live events on stage, my expertise ensures top-notch sound quality.
                </p>
                <p class="about-me-description text-slate-400 pb-5">
                Alongside my studies, I am actively involved in producing podcasts for Calvary Chapel located in Yakima, WA, where I combine my technical expertise with my passion for sound design.
                </p>
                <p class="about-me-description text-slate-400 pb-40">
                When I am not behind the mixing console, you can find me capturing moments through film photography, another creative outlet I enjoy. Feel free to connect with me through my social links or reach out to me on my contact page for any audio-related inquiries.
                </p>
            </div>
            <div class="about-me-image pb-60">
              <!-- Add your image here -->
              <img src="@/components/images/headshot.png" alt="Your Image" class="about-me-photo">
            </div>
          </div>
        </div>
      </div>
    </div>
  </template>
      
  <style scoped>
    .about-me-container {
      padding: 50px;
    }
    
    .about-me-content {
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    
    .about-me-text {
      flex: 1;
      max-width: 60%;
      padding-right: 20px;
    }
    
    .about-me-image {
      flex: 1;
      text-align: right;
      height: 64;
    }
    
    .about-me-photo {
      max-width: 100%;
      height: auto;
      border-radius: 8px;
    }
    
    .about-me-title {
      font-size: 36px;
      margin-bottom: 20px;
    }
    
    .about-me-description {
      font-size: 18px;
      line-height: 1.6;
    }
  
  </style>


<script setup lang="ts">
useHead({
  title: 'About',
  meta: [
    { name: 'description', content: 'Esterline Audio About Page.' }
  ],
  script: [ { innerHTML: 'console.log(\'Welcome to the About Page\')' } ]
})
</script>