<template>
  <div class="min-h-screen bg-gradient-to-r from-blue-500 via-purple-500 to-pink-500 flex items-center justify-center">
    <div class="bg-white/80 shadow-lg rounded-lg p-8 max-w-4xl w-full transform hover:scale-105 transition-transform duration-300">
      
      <div class="mb-8">
        <h3 class="text-2xl font-semibold text-gray-800 mb-4">Journey</h3>
        <swiper :slides-per-view="1" :space-between="30" class="mySwiper">
          <swiper-slide>
            <img src="./assets/images/friend.webp" alt="1" class="rounded-lg object-cover w-full h-64 transition-transform duration-300 hover:scale-105" />
          </swiper-slide>
          <swiper-slide>
            <img src="./assets/images/home pnf.jpg" alt="Foto 2" class="rounded-lg object-cover w-full h-64 transition-transform duration-300 hover:scale-105" />
          </swiper-slide>
          <swiper-slide>
            <img src="./assets/images/platipus.jpg" alt="Foto 3" class="rounded-lg object-cover w-full h-64 transition-transform duration-300 hover:scale-105" />
          </swiper-slide>
        </swiper>
      </div>

      <div class="flex flex-col md:flex-row items-center md:items-start">
        <div class="flex-shrink-0 mb-6 md:mb-0 md:mr-6">
          <img src="./assets/images/Profile_-_Phineas_Flynn.PNG.webp" alt="Profile" class="rounded-full w-32 h-32 object-cover border-4 border-blue-500 shadow-lg" />
        </div>
        <div class="bg-gray-900/50 p-4 rounded-lg">
          <h1 class="text-4xl font-bold text-white">Phineas Flynn</h1>
          <p class="text-lg text-gray-300 mt-1">Student</p>
          <p class="text-gray-300 mt-1">Danville, United States</p>
          <p class="text-gray-200 mt-4">
            "Welcome to my world! I'm a student who enjoys art and music. Here, I'll take you on a journey through this with a different perspective."
          </p>
        </div>
      </div>

      <div class="mt-8 grid grid-cols-1 md:grid-cols-2 gap-6">
        <div>
          <h3 class="text-lg font-semibold text-gray-800 mb-3">Skills</h3>
          <ul class="list-disc list-inside text-gray-700">
            <li>JavaScript, Vue.js, Nuxt.js</li>
            <li>HTML, CSS, Tailwind CSS</li>
            <li>Git, Version Control</li>
            <li>API Integration</li>
          </ul>
        </div>
        <div>
          <h3 class="text-lg font-semibold text-gray-800 mb-3">Experience</h3>
          <ul class="text-gray-700 space-y-2">
            <li>
              <strong>Freelance Software Developer</strong> - Nation company (2020 - present)
              <br />
              <strong>Some instrument at school band.</strong>
            </li>
            <li>
              <strong>Frontend Developer</strong> - Startup ABC (2018 - 2020)
              <br />
              Develop a small project with JavaScript dan Tailwind CSS.
            </li>
          </ul>
        </div>
      </div>

      <div class="mt-8">
        <h3 class="text-lg font-semibold text-gray-800 mb-3">Education</h3>
        <ul class="text-gray-700 space-y-2">
          <li>
            <strong>Monster University</strong> - Computer Science (present)
          </li>
        </ul>
      </div>

      <div class="mt-8">
        <h3 class="text-lg font-semibold text-gray-800 mb-3">Contact</h3>
        <ul class="text-gray-700 space-y-2">
          <li>Email: <a href="mailto:phineas.flynn@example.com" class="text-blue-500 hover:text-blue-600">phineas.flynn@example.com</a></li>
          <li>Phone: <a href="tel:+1234567890" class="text-blue-500 hover:text-blue-600">+1 234-567-890</a></li>
          <li>
            LinkedIn: <a href="https://www.linkedin.com/in/phineasflynn" target="_blank" class="text-blue-500 hover:text-blue-600">linkedin.com/in/phineasflynn</a>
          </li>
          <li>
            GitHub: <a href="https://github.com/phineasflynn" target="_blank" class="text-blue-500 hover:text-blue-600">github.com/phineasflynn</a>
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
import { Swiper, SwiperSlide } from 'swiper/vue';
import 'swiper/swiper-bundle.css';

export default {
  components: {
    Swiper,
    SwiperSlide
  },
  head() {
    return {
      title: "Profile",
    };
  },
};
</script>

<style scoped>
</style>
