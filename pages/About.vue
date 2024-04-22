<template>
    
    <div class="bg-gray-800 text-center text-white">
      <div class="text-5xl font-bold pt-10 pb-10">About</div>
    </div>
    
    <div class="about-me-container">
      <div class="about-me-content">
        <div class="about-me-text">
          <h2 class="about-me-title font-bold text-white">Let me introduce myself...</h2>
          <p class="about-me-description text-slate-400">
          I'm an audio engineer currently based in Kirkland, Washington, with a passion for music and sound. My journey into audio engineering began with a love for music and a curiosity about how it's created. From drawing inspiration from various interests like movies and television to producing music, I found my calling in the world of audio.
          Currently, I'm pursuing a major in Audio Production at Northwest University, where I'm honing my skills and deepening my understanding of sound engineering. My education in Audio Production from Northwest University has prepared me to be an engineer in live sound and music industry production. I'm proficient in sound editing, mixing, sound design, production audio, and live audio. With hands-on experience in recording equipment and software, coupled with a solid grasp of acoustic theory and track mixing, I'm equipped to deliver professional-grade audio works. Whether it's recording in the studio or producing live events on stage, my expertise ensures top-notch sound quality.
          Alongside my studies, I'm actively involved in producing podcasts for Calvary Chapel Yakima, combining my technical expertise with my passion for sound design.
            When I'm not behind the mixing console, you can find me capturing moments through film photography, another creative outlet I enjoy.
            Feel free to connect with me through my social links or reach out on my contact page for any audio-related inquiries.

          </p>
        </div>
        <div class="about-me-image">
          <!-- Add your image here -->
          <img src="@/components/images/headshot.png" alt="Your Image" class="about-me-photo">
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
