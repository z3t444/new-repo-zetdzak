<script setup>
  import Graph from "../components/Graph.vue"
  import "../assets/css/keyframes.css"
  import "../assets/css/responsive.css"
  import "../assets/css/shineText.css"
</script>

<template>
  <div class="dm_sans">
    <!-- //Graph Peformance// -->
    <div class="shine_text_light">
      <h2 class="text-center shine font-bold sm:text-4xl md:text-5xl lg:text-6xl lg:mt-36 dark:text-gray-100 dm_sans">Performance Us frontend & Backend</h2>
    </div>
    <div class="prgh">
      <p class="p-8 max_paragraph sm:text-lg mt-10 dm_sans text-center mx-auto text-gray-700 dark:text-gray-300 lg:w-11/12">ZetDzak takes chat and collaboration to the next level: daily standups, team check-ins, surveys, kudos, best companion bot for your virtual watercooler, motivation <span class="light_lamp">💡</span></p>
    </div>
    <!-- // -->

    <div class="flex flex-col justify-between items-center sm:flex-row mt-40 gap-10">
      <div class="p-4 w-full sm:w-1/2">
        <p class="text-orange-400">Master of Management System</p>
        <h3 class="dark:text-gray-200 font-medium mt-2 text-5xl leading-tight">
          Manage All <span class="system_text_css">system</span> and <br />
          data <span class="security_text_css">Security</span>
        </h3>
        <p class="dark:text-gray-200 mt-8 leading-8">
          Lorem ipsum dolor sit amet consectetur, adipisicing elit. Voluptatum necessitatibus <br />
          beatae perspiciatis porro cumque tempore, ipsa similique omnis voluptates esse!
        </p>
        <p class="dark:text-gray-200 mt-7 leading-8">
          Lorem ipsum dolor sit, amet consectetur <br />
          adipisicing elit.
        </p>
        <div class="flex items-center flex-col sm:flex-row md:flex-col lg:flex-row mt-10 gap-10">
          <a href="#" class="bg-blue-400 dark:text-gray-200 hover:bg-transparent hover:border text-black hover:border-blue-400 text-center w-36 duration-100 p-4 rounded-full">Read More</a>
          <div class="p-4 w-full sm:w-1/2 md:w-full dark:text-gray-200 lg:w-1/3 system_text_css">
            <h3 class="text-5xl font-medium">78%</h3>
            <p class="mt-3">Lorem, ipsum dolor.</p>
          </div>
          <div class="p-4 w-full sm:w-1/2 md:w-full lg:w-1/3 security_text_css">
            <h3 class="text-5xl font-medium">80%</h3>
            <p class="mt-3">Lorem ipsum dolor sit.</p>
          </div>
        </div>
      </div>
      <div class="p-4 w-full sm:w-1/2 rounded-2xl">
        <div class="for_import">
          <Graph />
        </div>
      </div>
    </div>

    <section class="ClassName dm_sans">
      <div class="container px-6 py-10 mx-auto mt-40">
        <h1 class="text-2xl font-medium text-center text-gray-800 capitalize lg:text-5xl dark:text-gray-200">gallery For Us Peformance</h1>

        <div class="class_grid_image grid grid-cols-1 sm:gap xl:mt-20 xl:gap-12 lg:grid-cols-2">
          <div class="gallery_items_img flex items-end overflow-hidden bg-cover rounded-2xl h-96 hover:scale-105 duration-100" style="background-image: url('https://images.unsplash.com/photo-1621111848501-8d3634f82336?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1565&q=80')">
            <div class="w-full px-8 py-4 overflow-hidden rounded-b-lg backdrop-blur-sm bg-white/60 dark:bg-gray-800/60">
              <h2 class="mt-4 text-xl font-semibold text-gray-800 capitalize dark:text-white">Best website collections</h2>
              <p class="mt-2 text-lg tracking-wider text-blue-500 uppercase dark:text-blue-400">Website</p>
            </div>
          </div>

          <div class="gallery_items_img2 flex items-end overflow-hidden bg-cover rounded-2xl h-96 hover:scale-105 duration-100" style="background-image: url('https://images.unsplash.com/photo-1621609764180-2ca554a9d6f2?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=764&q=80')">
            <div class="w-full px-8 py-4 overflow-hidden rounded-b-lg backdrop-blur-sm bg-white/60 dark:bg-gray-800/60">
              <h2 class="mt-4 text-xl font-semibold text-gray-800 capitalize dark:text-white">Block of Ui kit collections</h2>
              <p class="mt-2 text-lg tracking-wider text-blue-500 uppercase dark:text-blue-400">Ui kit</p>
            </div>
          </div>

          <div class="gallery_items_img3 flex items-end overflow-hidden bg-cover rounded-2xl h-96 hover:scale-105 duration-100" style="background-image: url('https://images.unsplash.com/photo-1531403009284-440f080d1e12?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1470&q=80')">
            <div class="w-full px-8 py-4 overflow-hidden rounded-b-lg backdrop-blur-sm bg-white/60 dark:bg-gray-800/60">
              <h2 class="mt-4 text-xl font-semibold text-gray-800 capitalize dark:text-white">Ton’s of mobile mockup</h2>
              <p class="mt-2 text-lg tracking-wider text-blue-500 uppercase dark:text-blue-400">Mockups</p>
            </div>
          </div>

          <div class="gallery_items_img flex items-end overflow-hidden bg-cover rounded-2xl h-96 hover:scale-105 duration-100" style="background-image: url('https://images.unsplash.com/photo-1603380353725-f8a4d39cc41e?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1470&q=80')">
            <div class="w-full px-8 py-4 overflow-hidden rounded-b-lg backdrop-blur-sm bg-white/60 dark:bg-gray-800/60">
              <h2 class="mt-4 text-xl font-semibold text-gray-800 capitalize dark:text-white">Huge collection of animation</h2>
              <p class="mt-2 text-lg tracking-wider text-blue-500 uppercase dark:text-blue-400">Animation</p>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<style>
  .max_paragraph {
    max-width: 680px;
  }

  .Explore_our_leading {
    line-height: 50px;
  }
</style>
