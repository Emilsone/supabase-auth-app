<template>
  <main class="hero-font">
    <Header />
    <section class="text-gray-600 ">
      <div class="container mx-auto flex px-5 py-24 md:flex-row flex-col items-center">
        <div
          class="lg:flex-grow md:w-1/2 lg:pr-24 md:pr-16 flex flex-col md:items-start md:text-left mb-16 md:mb-0 items-center text-center hero-text">
          <h1 class="title-font sm:text-5xl text-3xl mb-8 font-bold text-gray-900">Welcome to TechEd 🎉🎉
          </h1>
          <p class="mb-12 leading-relaxed paragraph-text"> At TechEd, we cultivate an environment where students excel in technology education. Our expert faculty and innovative curriculum support each student's unique learning path. With cutting-edge facilities and diverse tech-focused activities, we provide the resources and opportunities for students to explore their interests and reach their full potential in the tech industry. </p>
          <div class="flex justify-center items-center enrol-btn">

            <a class="flex items-center py-4 px-10 bg-btn text-md " href="#">
              Apply Now
              <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                stroke="currentColor" class="w-6 h-6 ml-2">
                <path stroke-linecap="round" stroke-linejoin="round" d="M17.25 8.25L21 12m0 0l-3.75 3.75M21 12H3" />
              </svg>

            </a>

            <a class="w-12 h-12 inline-flex items-center justify-center rounded-full bg-gray-100 mb-1 ml-8 enrol-btn"
              href="https">
              <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                stroke="currentColor" class="w-6 h-6">
                <path stroke-linecap="round" stroke-linejoin="round"
                  d="M5.25 5.653c0-.856.917-1.398 1.667-.986l11.54 6.348a1.125 1.125 0 010 1.971l-11.54 6.347a1.125 1.125 0 01-1.667-.985V5.653z" />
              </svg>

            </a>
            <span class="items-center px-2 text-black">
              View Tech Courses
            </span>
          </div>
        </div>
        <div class="lg:max-w-lg lg:w-full md:w-1/2 w-5/6">
          <img class="object-cover object-center rounded hero-image" alt="hero" src="../static/pana.png">
        </div>
      </div>
    </section>
  </main>
</template>

<script>
import Header from '../components/Header.vue';
export default {
  name: 'FileUploader',
  components: {
    Header
  }
}


</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Work+Sans&display=swap');

.hero-font {
  font-family: 'Work Sans', sans-serif;
}
</style>
