<script setup>
  import Graph from "../components/Graph.vue"
  import "../assets/css/keyframes.css"
  import "../assets/css/responsive.css"
  import "../assets/css/shineText.css"

  // import Carousel About

  // Inisialisasi slick-carousel

  // import Ico
  import GithubIco from "../assets/ico/githubIco.vue"
  import facebookIco from "../assets/ico/facebookIco.vue"
  import Insta from "../assets/ico/insta.vue"
</script>

<template>
  <div class="dm_sans shadow_collor">
    <!-- //Graph Peformance// -->
    <div class="bg_glow_color">
      <div class="shine_text_light">
        <h2 class="text-center shine font-bold sm:text-4xl md:text-5xl lg:text-6xl lg:mt-52 dark:text-gray-100 dm_sans">Performance Us frontend & Backend</h2>
      </div>
      <div class="prgh">
        <p class="p-8 max_paragraph sm:text-lg mt-10 dm_sans text-center mx-auto text-gray-700 dark:text-gray-300 lg:w-11/12">ZetDzak takes chat and collaboration to the next level: daily standups, team check-ins, surveys, kudos, best companion bot for your virtual watercooler, motivation <span class="light_lamp">💡</span></p>
      </div>
    </div>
    <!-- // -->

    <div class="flex flex-col justify-between items-center sm:flex-row mt-20 gap-10">
      <div class="p-1 w-full sm:w-1/2">
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

    <div class="ClassName mt-36 flex p-10 bg-gray-200 dark:bg-gray-900 rounded-3xl items-center justify-around">
      <div class="ClassName">
        <p class="text-orange-400 text-lg">Dzaky</p>
        <h3 class="text-5xl font-medium mt-4 dark:text-gray-200">Easy Program</h3>
        <p class="mt-5 leading-8">
          Lorem ipsum dolor sit amet consectetur <br />
          adipisicing elit. Sit, vitae.
        </p>

        <div class="flex space-x-6 justify-start mt-10">
          <div class="p-2 dark:bg-gray-900 rounded-full hover:scale-110 duration-100">
            <facebookIco />
          </div>
          <div class="p-2 dark:bg-gray-900 rounded-full hover:scale-110 duration-100">
            <Insta />
          </div>
          <div class="p-2 dark:bg-gray-900 rounded-full hover:scale-110 duration-100">
            <a href="#" class="text-gray-500 hover:text-blue-500">
              <svg class="h-5 w-5" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true">
                <path d="M8.29 20.251c7.547 0 11.675-6.253 11.675-11.675 0-.178 0-.355-.012-.53A8.348 8.348 0 0022 5.92a8.19 8.19 0 01-2.357.646 4.118 4.118 0 001.804-2.27 8.224 8.224 0 01-2.605.996 4.107 4.107 0 00-6.993 3.743 11.65 11.65 0 01-8.457-4.287 4.106 4.106 0 001.27 5.477A4.072 4.072 0 012.8 9.713v.052a4.105 4.105 0 003.292 4.022 4.095 4.095 0 01-1.853.07 4.108 4.108 0 003.834 2.85A8.233 8.233 0 012 18.407a11.616 11.616 0 006.29 1.84"></path>
              </svg>
            </a>
          </div>
          <div class="p-2 dark:bg-gray-900 rounded-full hover:scale-110 duration-100">
            <GithubIco />
          </div>
          <div class="p-2 dark:bg-gray-900 rounded-full hover:scale-110 duration-100">
            <a href="#" class="text-gray-500 hover:text-blue-500">
              <svg class="h-5 w-5" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true">
                <path
                  fill-rule="evenodd"
                  d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10c5.51 0 10-4.48 10-10S17.51 2 12 2zm6.605 4.61a8.502 8.502 0 011.93 5.314c-.281-.054-3.101-.629-5.943-.271-.065-.141-.12-.293-.184-.445a25.416 25.416 0 00-.564-1.236c3.145-1.28 4.577-3.124 4.761-3.362zM12 3.475c2.17 0 4.154.813 5.662 2.148-.152.216-1.443 1.941-4.48 3.08-1.399-2.57-2.95-4.675-3.189-5A8.687 8.687 0 0112 3.475zm-3.633.803a53.896 53.896 0 013.167 4.935c-3.992 1.063-7.517 1.04-7.896 1.04a8.581 8.581 0 014.729-5.975zM3.453 12.01v-.26c.37.01 4.512.065 8.775-1.215.25.477.477.965.694 1.453-.109.033-.228.065-.336.098-4.404 1.42-6.747 5.303-6.942 5.629a8.522 8.522 0 01-2.19-5.705zM12 20.547a8.482 8.482 0 01-5.239-1.8c.152-.315 1.888-3.656 6.703-5.337.022-.01.033-.01.054-.022a35.318 35.318 0 011.823 6.475 8.4 8.4 0 01-3.341.684zm4.761-1.465c-.086-.52-.542-3.015-1.659-6.084 2.679-.423 5.022.271 5.314.369a8.468 8.468 0 01-3.655 5.715z"
                  clip-rule="evenodd"></path>
              </svg>
            </a>
          </div>
        </div>
      </div>
      <!-- image  -->
      <div class="ClassName">
        <img src="../assets/img/coding.jpeg" class="rounded-3xl hover:scale-105 duration-100 hover:border-gray-800" width="450px" alt="" />
      </div>

      <div class="ClassName text-end">
        <p class="text-orange-400 text-lg">Zet</p>
        <h3 class="text-5xl font-medium mt-4 dark:text-gray-200">Easy Layout</h3>
        <p class="mt-5 leading-8">
          Lorem ipsum dolor sit amet consectetur <br />
          adipisicing elit. Sit, vitae.
        </p>

        <div class="flex space-x-6 justify-start mt-10">
          <div class="p-2 dark:bg-gray-900 rounded-full hover:scale-110 duration-100">
            <facebookIco />
          </div>
          <div class="p-2 dark:bg-gray-900 rounded-full hover:scale-110 duration-100">
            <Insta />
          </div>
          <div class="p-2 dark:bg-gray-900 rounded-full hover:scale-110 duration-100">
            <a href="#" class="text-gray-500 hover:text-blue-500">
              <svg class="h-5 w-5" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true">
                <path d="M8.29 20.251c7.547 0 11.675-6.253 11.675-11.675 0-.178 0-.355-.012-.53A8.348 8.348 0 0022 5.92a8.19 8.19 0 01-2.357.646 4.118 4.118 0 001.804-2.27 8.224 8.224 0 01-2.605.996 4.107 4.107 0 00-6.993 3.743 11.65 11.65 0 01-8.457-4.287 4.106 4.106 0 001.27 5.477A4.072 4.072 0 012.8 9.713v.052a4.105 4.105 0 003.292 4.022 4.095 4.095 0 01-1.853.07 4.108 4.108 0 003.834 2.85A8.233 8.233 0 012 18.407a11.616 11.616 0 006.29 1.84"></path>
              </svg>
            </a>
          </div>
          <div class="p-2 dark:bg-gray-900 rounded-full hover:scale-110 duration-100">
            <GithubIco />
          </div>
          <div class="p-2 dark:bg-gray-900 rounded-full hover:scale-110 duration-100">
            <a href="#" class="text-gray-500 hover:text-blue-500">
              <svg class="h-5 w-5" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true">
                <path
                  fill-rule="evenodd"
                  d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10c5.51 0 10-4.48 10-10S17.51 2 12 2zm6.605 4.61a8.502 8.502 0 011.93 5.314c-.281-.054-3.101-.629-5.943-.271-.065-.141-.12-.293-.184-.445a25.416 25.416 0 00-.564-1.236c3.145-1.28 4.577-3.124 4.761-3.362zM12 3.475c2.17 0 4.154.813 5.662 2.148-.152.216-1.443 1.941-4.48 3.08-1.399-2.57-2.95-4.675-3.189-5A8.687 8.687 0 0112 3.475zm-3.633.803a53.896 53.896 0 013.167 4.935c-3.992 1.063-7.517 1.04-7.896 1.04a8.581 8.581 0 014.729-5.975zM3.453 12.01v-.26c.37.01 4.512.065 8.775-1.215.25.477.477.965.694 1.453-.109.033-.228.065-.336.098-4.404 1.42-6.747 5.303-6.942 5.629a8.522 8.522 0 01-2.19-5.705zM12 20.547a8.482 8.482 0 01-5.239-1.8c.152-.315 1.888-3.656 6.703-5.337.022-.01.033-.01.054-.022a35.318 35.318 0 011.823 6.475 8.4 8.4 0 01-3.341.684zm4.761-1.465c-.086-.52-.542-3.015-1.659-6.084 2.679-.423 5.022.271 5.314.369a8.468 8.468 0 01-3.655 5.715z"
                  clip-rule="evenodd"></path>
              </svg>
            </a>
          </div>
        </div>
      </div>
    </div>

    <section class="ClassName dm_sans">
      <div class="container px-6 py-10 mx-auto mt-80">
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

    <section>
      <div class="other_gallery_card mt-20">
        <div class="line_vertical mx-auto flex justify-center">
          <svg xmlns="http://www.w3.org/2000/svg" width="50" height="117" viewBox="0 0 50 147" fill="none">
            <path fill-rule="evenodd" clip-rule="evenodd" d="M25 3.675C24.6685 3.675 24.3505 4.06219 24.1161 4.75138C23.8817 5.44058 23.75 6.37533 23.75 7.35V139.65C23.75 140.625 23.8817 141.559 24.1161 142.249C24.3505 142.938 24.6685 143.325 25 143.325C25.3315 143.325 25.6495 142.938 25.8839 142.249C26.1183 141.559 26.25 140.625 26.25 139.65V7.35C26.25 6.37533 26.1183 5.44058 25.8839 4.75138C25.6495 4.06219 25.3315 3.675 25 3.675Z" fill="#A8A8A8" />
          </svg>
        </div>
        <div class="image_square">
          <div class="desk_image_square text-center dark:text-gray-200 mt-10">
            <h3 class="text-4xl font-medium">Other Our Actifity</h3>
            <p class="mt-5 leading-8">
              Lorem ipsum, dolor sit amet consectetur adipisicing elit. <br />
              Pariatur modi veritatis cupiditate assumenda possimus quaerat.
            </p>
          </div>
        </div>

        <!-- //galely grid square -->
        <div class="flex flex-wrap mx-auto justify-center mt-10 p-2 gap-2 rounded-3xl">
          <div class="w-full sm:w-1/2 md:w-1/4 lg:w-1/4 xl:w-1/4 p-4">
            <img class="rounded-2xl hover:scale-105 duration-100" src="../assets/img/zet.jpg" alt="" />
          </div>
          <div class="w-full sm:w-1/2 md:w-1/4 lg:w-1/4 xl:w-1/4 p-4">
            <img class="rounded-2xl hover:scale-105 duration-100" src="../assets/img/akaksayangg.png" alt="" />
          </div>
          <div class="w-full sm:w-1/2 md:w-1/4 lg:w-1/4 xl:w-1/4 p-4">
            <img class="rounded-2xl hover:scale-105 duration-100" src="../assets/img/akaksayangg.png" alt="" />
          </div>
        </div>
        <div class="flex flex-wrap mx-auto justify-center mt-2 p-2 gap-2 rounded-3xl">
          <div class="w-full sm:w-1/2 md:w-1/4 lg:w-1/4 xl:w-1/4 p-4">
            <img class="rounded-2xl hover:scale-105 duration-100" src="../assets/img/zet.jpg" alt="" />
          </div>
          <div class="w-full sm:w-1/2 md:w-1/4 lg:w-1/4 xl:w-1/4 p-4">
            <img class="rounded-2xl hover:scale-105 duration-100" src="../assets/img/akaksayangg.png" alt="" />
          </div>
          <div class="w-full sm:w-1/2 md:w-1/4 lg:w-1/4 xl:w-1/4 p-4">
            <img class="rounded-2xl hover:scale-105 duration-100" src="../assets/img/akaksayangg.png" alt="" />
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
