<script setup>
  import "../assets/css/responsive.css"
  import "../assets/css/graphpie.css"
  import "../views/style/BlogView.css"
  import GithubIco from "../assets/ico/githubIco.vue"
  import facebookIco from "../assets/ico/facebookIco.vue"
  import Insta from "../assets/ico/insta.vue"
  import pcIco from "../assets/ico/pcIco.vue"

  import messageIco from "@/assets/ico/messageIco.vue"
  import locationIco from '../assets/ico/locationIco.vue'
</script>

<template>
  <div class="ClasAll">
    <section>
      <div class="mt-20">
        <div class="xl:container m-auto px-6 text-gray-600 md:px-12">
          <div class="dark:lg:bg-darker rounded-[4rem] md:flex flex-row-reverse md:gap-6 justify-between mx-auto md:space-y-0 lg:items-center">
            <div class="md:5/12 lg:w-1/2">
              <img src="../assets/img/staravatar.png" class="mx-auto image-hero-blog animate-up-down duration-100" alt="image" loading="lazy" width="500px" height="" />
            </div>
            <div class="md:7/12 lg:w-1/2">
              <h2 class="text-2xl sm:text-3xl font-medium desk_avatarstar text-gray-900 md:text-4xl lg:text-5xl text-center xl:text-[50px] xl:text-start sm:text-center xl:leading-tight leading-normal dark:text-gray-200">We maintain the development ecosystem of every framework that we run.</h2>
              <p class="my-8 text-gray-600 leading-8 text-center xl:text-start xl:text-lg xl:leading-9 text-sm dark:text-gray-300">Nobis minus voluptatibus pariatur dignissimos libero quaerat iure expedita at? Asperiores nemo possimus nesciunt dicta veniam aspernatur quam mollitia.</p>
              <div class="divide-y space-y-4 divide-gray-100 dark:divide-gray-800">
                <div class="mt-20 flex gap-4 md:items-center hover:scale-105 duration-100">
                  <div class="w-12 h-12 flex gap-4 rounded-full bg-indigo-100 dark:bg-indigo-900/20">
                   <messageIco/>
                  </div>
                  <div class="w-5/6">
                    <h3 class="font-semibold text-lg text-gray-700 dark:text-indigo-300">Chat Anytime</h3>
                    <p class="text-gray-500 mt-3 text-sm dark:text-gray-400">Asperiores nemo possimus nesciunt quam mollitia.</p>
                  </div>
                </div>
                <div class="pt-4 flex gap-4 md:items-center hover:scale-105 duration-100">
                  <div class="w-12 h-12 flex gap-4 rounded-full bg-teal-100 dark:bg-teal-900/20">
                   <locationIco/>
                  </div>
                  <div class="w-5/6">
                    <h3 class="font-semibold text-lg text-gray-700 dark:text-teal-300">Real Time Location</h3>
                    <p class="text-gray-500 mt-3 text-sm dark:text-gray-400">Asperiores nemo possimus nesciunt quam mollitia.</p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="mt-60">
      <div class="ClassName xl:p-0 p-5">
        <h3 class="xl:text-4xl text-2xl leading-9 text-start dark:text-gray-200">Seamless <span class="dark:text-blue-400 font-semibold" style="text-shadow: 0px 0px 20px;">integration</span> with your existing <span class="dark:text-sky-400 font-semibold" style="text-shadow: 0px 0px 20px;">ecosystem</span>.</h3>
        <p class="dark:text-gray-300 xl:text-lg xl:w-1/3 xl:leading-9 mt-8">List of packages to extend your Refine project with UI frameworks, backend connectors and other powerful tools.</p>
      </div>
      <div class="border-t border-gray-800 mt-12 h-5"></div>
      <div class="ClassName mt-10">
        <h3 class="ClassName xl:text-3xl p-5 pb-1 xl:p-0 dark:text-gray-200 font-semibold">UI an DB framework</h3>
      </div>
      <div class="flex flex-wrap justify-center mt-10 xl:mt-14">
        <div class="w-full sm:w-1/2 lg:w-2/4 p-4 hover:scale-105 duration-100">
          <div class="h-32 sm:h-48 lg:h-58 rounded-3xl shadow-md dark:border hover:bg-[#1c1c2e] dark:border-gray-800">
            <p class="text-white text-center">Box 1</p>
          </div>
        </div>
        <div class="w-full sm:w-1/2 lg:w-2/4 p-4 hover:scale-105 duration-100">
          <div class="h-32 sm:h-48 lg:h-58 rounded-3xl shadow-md dark:border hover:bg-[#1c1c2e] dark:border-gray-800">
            <p class="text-white text-center">Box 2</p>
          </div>
        </div>
      </div>
      <div class="flex flex-wrap justify-center xl:mt-10">
        <div class="w-full sm:w-1/2 lg:w-2/4 p-4 hover:scale-105 duration-100">
          <div class="h-32 sm:h-48 lg:h-58 rounded-3xl shadow-md dark:border hover:bg-[#1c1c2e] dark:border-gray-800">
            <p class="text-white text-center">Box 1</p>
          </div>
        </div>
        <div class="w-full sm:w-1/2 lg:w-2/4 p-4 hover:scale-105 duration-100">
          <div class="h-32 sm:h-48 lg:h-58 rounded-3xl shadow-md dark:border hover:bg-[#1c1c2e] dark:border-gray-800">
            <p class="text-white text-center">Box 2</p>
          </div>
        </div>
      </div>
      <div class="flex flex-wrap justify-center xl:mt-10">
        <div class="w-full sm:w-1/2 lg:w-2/4 p-4 hover:scale-105 duration-100">
          <div class="h-32 sm:h-48 lg:h-58 rounded-3xl shadow-md dark:border hover:bg-[#1c1c2e] dark:border-gray-800">
            <p class="text-white text-center">Box 1</p>
          </div>
        </div>
        <div class="w-full sm:w-1/2 lg:w-2/4 p-4">
          <div class="h-32 sm:h-48 lg:h-58 rounded-3xl shadow-md dark:border hover:bg-[#1c1c2e] dark:border-gray-800">
            <p class="text-white text-center">Box 2</p>
          </div>
        </div>
      </div>
      <div class="flex flex-wrap justify-center xl:mt-10">
        <div class="w-full sm:w-1/2 lg:w-2/4 p-4 hover:scale-105 duration-100">
          <div class="h-32 sm:h-48 lg:h-58 rounded-3xl shadow-md dark:border hover:bg-[#1c1c2e] dark:border-gray-800">
            <p class="text-white text-center">Box 1</p>
          </div>
        </div>
        <div class="w-full sm:w-1/2 lg:w-2/4 p-4 hover:scale-105 duration-100">
          <div class="h-32 sm:h-48 lg:h-58 rounded-3xl shadow-md dark:border hover:bg-[#1c1c2e] dark:border-gray-800">
            <p class="text-white text-center">Box 2</p>
          </div>
        </div>
      </div>
    </section>

    <section class="mt-44">
      <div class="flex flex-wrap justify-center xl:mt-10">
        <div class="w-full sm:w-1/2 lg:w-2/4 p-4 hover:scale-105 duration-100">
          <div class="h-32 sm:h-48 lg:h-58 rounded-3xl shadow-md dark:border hover:bg-[#1c1c2e] dark:border-gray-800">
            <p class="text-white text-center">Box 1</p>
          </div>
        </div>
        <div class="w-full sm:w-1/2 lg:w-2/4 p-4 hover:scale-105 duration-100">
          <div class="h-32 sm:h-48 lg:h-58 rounded-3xl shadow-md dark:border hover:bg-[#1c1c2e] dark:border-gray-800">
            <p class="text-white text-center">Box 2</p>
          </div>
        </div>
      </div>
      <div class="flex flex-wrap justify-center xl:mt-10">
        <div class="w-full sm:w-1/2 lg:w-2/4 p-4 hover:scale-105 duration-100">
          <div class="h-32 sm:h-48 lg:h-58 rounded-3xl shadow-md dark:border hover:bg-[#1c1c2e] dark:border-gray-800">
            <p class="text-white text-center">Box 1</p>
          </div>
        </div>
        <div class="w-full sm:w-1/2 lg:w-2/4 p-4 hover:scale-105 duration-100">
          <div class="h-32 sm:h-48 lg:h-58 rounded-3xl shadow-md dark:border hover:bg-[#1c1c2e] dark:border-gray-800">
            <p class="text-white text-center">Box 2</p>
          </div>
        </div>
      </div>
    </section>

    <section class="ClassName mt-44">
      <div class="container px-6 py-10 mx-auto">
        <h1 class="text-2xl font-semibold text-gray-800 capitalize leading-8 lg:text-3xl dark:text-white">explore our awesome <span class="dark:text-red-500" style="text-shadow: 0px 0px 20px;">Components</span>🔍</h1>
        <p class="mt-4 text-gray-500 xl:mt-8 leading-8 dark:text-gray-300 xl:text-lg xl:leading-9 xl:w-2/6">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Nostrum quam voluptatibus</p>

        <div class="grid grid-cols-1 gap-8 mt-12 xl:mt-20 xl:gap-17 md:grid-cols-2 xl:grid-cols-3">
          <div class="space-y-3 p-10 rounded-3xl hover:scale-105 duration-100" style="background-color: #1c1c2e">
            <span class="inline-block p-3 text-blue-500 bg-blue-100 rounded-full dark:text-white dark:bg-red-500  shadow-red-500">
              <svg xmlns="http://www.w3.org/2000/svg" class="w-6 h-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5H7a2 2 0 00-2 2v12a2 2 0 002 2h10a2 2 0 002-2V7a2 2 0 00-2-2h-2M9 5a2 2 0 002 2h2a2 2 0 002-2M9 5a2 2 0 012-2h2a2 2 0 012 2m-3 7h3m-3 4h3m-6-4h.01M9 16h.01" />
              </svg>
            </span>
            <h1 class="text-xl font-semibold text-gray-700 capitalize dark:text-white">Copy & paste components</h1>
            <p class="text-gray-500 text-sm leading-7 dark:text-gray-300">Lorem ipsum dolor sit amet consectetur adipisicing elit. Provident ab nulla quod dignissimos vel non corrupti doloribus voluptatum eveniet</p>
          </div>

          <div class="space-y-3 p-10 rounded-3xl hover:scale-105 duration-100" style="background-color: #1c1c2e">
            <span class="inline-block p-3 text-blue-500 bg-blue-100 rounded-full dark:text-white dark:bg-blue-500">
              <svg xmlns="http://www.w3.org/2000/svg" class="w-6 h-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6V4m0 2a2 2 0 100 4m0-4a2 2 0 110 4m-6 8a2 2 0 100-4m0 4a2 2 0 110-4m0 4v2m0-6V4m6 6v10m6-2a2 2 0 100-4m0 4a2 2 0 110-4m0 4v2m0-6V4" />
              </svg>
            </span>
            <h1 class="text-xl font-semibold text-gray-700 capitalize dark:text-white">Zero Configuration</h1>
            <p class="text-gray-500 text-sm leading-7 dark:text-gray-300">Lorem ipsum dolor sit amet consectetur adipisicing elit. Provident ab nulla quod dignissimos vel non corrupti doloribus voluptatum eveniet</p>
          </div>

          <div class="space-y-3 p-10 rounded-3xl hover:scale-105 duration-100" style="background-color: #1c1c2e">
            <span class="inline-block p-3 text-blue-500 bg-blue-100 rounded-full dark:text-white dark:bg-orange-500">
              <svg xmlns="http://www.w3.org/2000/svg" class="w-6 h-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 19v-6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2a2 2 0 002-2zm0 0V9a2 2 0 012-2h2a2 2 0 012 2v10m-6 0a2 2 0 002 2h2a2 2 0 002-2m0 0V5a2 2 0 012-2h2a2 2 0 012 2v14a2 2 0 01-2 2h-2a2 2 0 01-2-2z" />
              </svg>
            </span>
            <h1 class="text-xl font-semibold text-gray-700 capitalize dark:text-white">New Components Every month</h1>
            <p class="text-gray-500 text-sm leading-7 dark:text-gray-300">Lorem ipsum dolor sit amet consectetur adipisicing elit. Provident ab nulla quod dignissimos vel non corrupti doloribus voluptatum eveniet</p>
          </div>

          <div class="space-y-3 p-10 rounded-3xl hover:scale-105 duration-100" style="background-color: #1c1c2e">
            <span class="inline-block p-3 text-blue-500 bg-blue-100 rounded-full dark:text-white dark:bg-green-500">
              <svg xmlns="http://www.w3.org/2000/svg" class="w-6 h-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 18.657A8 8 0 016.343 7.343S7 9 9 10c0-2 .5-5 2.986-7C14 5 16.09 5.777 17.656 7.343A7.975 7.975 0 0120 13a7.975 7.975 0 01-2.343 5.657z" />
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9.879 16.121A3 3 0 1012.015 11L11 14H9c0 .768.293 1.536.879 2.121z" />
              </svg>
            </span>
            <h1 class="text-xl font-semibold text-gray-700 capitalize dark:text-white">elegant Dark Mode</h1>
            <p class="text-gray-500 text-sm leading-7 dark:text-gray-300">Lorem ipsum dolor sit amet consectetur adipisicing elit. Provident ab nulla quod dignissimos vel non corrupti doloribus voluptatum eveniet</p>
          </div>

          <div class="space-y-3 p-10 rounded-3xl hover:scale-105 duration-100" style="background-color: #1c1c2e">
            <span class="inline-block p-3 text-blue-500 bg-blue-100 rounded-full dark:text-white dark:bg-purple-500">
              <svg xmlns="http://www.w3.org/2000/svg" class="w-6 h-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M11 4a2 2 0 114 0v1a1 1 0 001 1h3a1 1 0 011 1v3a1 1 0 01-1 1h-1a2 2 0 100 4h1a1 1 0 011 1v3a1 1 0 01-1 1h-3a1 1 0 01-1-1v-1a2 2 0 10-4 0v1a1 1 0 01-1 1H7a1 1 0 01-1-1v-3a1 1 0 00-1-1H4a2 2 0 110-4h1a1 1 0 001-1V7a1 1 0 011-1h3a1 1 0 001-1V4z" />
              </svg>
            </span>
            <h1 class="text-xl font-semibold text-gray-700 capitalize dark:text-white">Easy to customiztions</h1>
            <p class="text-gray-500 text-sm leading-7 dark:text-gray-300">Lorem ipsum dolor sit amet consectetur adipisicing elit. Provident ab nulla quod dignissimos vel non corrupti doloribus voluptatum eveniet</p>
          </div>

          <div class="space-y-3 p-10 rounded-3xl hover:scale-105 duration-100" style="background-color: #1c1c2e">
           rea
            <h1 class="text-xl font-semibold text-gray-700 capitalize dark:text-white">Simple & clean designs</h1>
            <p class="text-gray-500 text-sm leading-7 dark:text-gray-300">Lorem ipsum dolor sit amet consectetur adipisicing elit. Provident ab nulla quod dignissimos vel non corrupti doloribus voluptatum eveniet</p>
          </div>
        </div>
      </div>
    </section>

    <section class="ClassName mt-20">
      <div class="container px-6 py-10 mx-auto">
        <h1 class="text-2xl font-medium text-gray-800 capitalize lg:text-3xl dark:text-white">explore our awesome <span class="underline decoration-blue-500">Components</span></h1>

        <p class="mt-4 text-gray-500 xl:mt-6 xl:w-1/3 leading-8 xl:text-lg xl:leading-9 dark:text-gray-300">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Nostrum quam voluptatibus</p>
        <div class="grid grid-cols-1 gap-8 mt-8 xl:mt-20 xl:gap-8 md:grid-cols-2 xl:grid-cols-3">
          <div class="p-8 space-y-6 border border-gray-400 dark:border-gray-800 hover:dark:border-sky-400 rounded-3xl hover:scale-105 duration-100">
            <span class="inline-block text-blue-500 dark:text-red-500">
              <svg xmlns="http://www.w3.org/2000/svg" class="w-8 h-8" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 18.657A8 8 0 016.343 7.343S7 9 9 10c0-2 .5-5 2.986-7C14 5 16.09 5.777 17.656 7.343A7.975 7.975 0 0120 13a7.975 7.975 0 01-2.343 5.657z" />
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9.879 16.121A3 3 0 1012.015 11L11 14H9c0 .768.293 1.536.879 2.121z" />
              </svg>
            </span>
            <h1 class="text-2xl font-semibold text-gray-700 capitalize dark:text-white">elegant Dark Mode</h1>
            <p class="text-gray-500 text-sm leading-7 dark:text-gray-300">Lorem ipsum dolor sit amet consectetur adipisicing elit. Provident ab nulla quod dignissimos vel non corrupti doloribus voluptatum eveniet</p>
          </div>

          <div class="p-8 space-y-6 border border-blue-400 dark:border-gray-800 hover:dark:border-sky-400 rounded-3xl hover:scale-105 duration-100">
            <span class="inline-block text-blue-500 dark:text-blue-400">
              <svg xmlns="http://www.w3.org/2000/svg" class="w-8 h-8" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M11 4a2 2 0 114 0v1a1 1 0 001 1h3a1 1 0 011 1v3a1 1 0 01-1 1h-1a2 2 0 100 4h1a1 1 0 011 1v3a1 1 0 01-1 1h-3a1 1 0 01-1-1v-1a2 2 0 10-4 0v1a1 1 0 01-1 1H7a1 1 0 01-1-1v-3a1 1 0 00-1-1H4a2 2 0 110-4h1a1 1 0 001-1V7a1 1 0 011-1h3a1 1 0 001-1V4z" />
              </svg>
            </span>
            <h1 class="text-2xl font-semibold text-gray-700 capitalize dark:text-white">Easy to customiztions</h1>
            <p class="text-gray-500 text-sm leading-7 dark:text-gray-300">Lorem ipsum dolor sit amet consectetur adipisicing elit. Provident ab nulla quod dignissimos vel non corrupti doloribus voluptatum eveniet</p>
          </div>

          <div class="p-8 space-y-6 border border-blue-400 dark:border-gray-800 hover:dark:border-sky-400 rounded-3xl hover:scale-105 duration-100">
            <span class="inline-block text-blue-500 dark:text-yellow-400">
              <svg xmlns="http://www.w3.org/2000/svg" class="w-8 h-8" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 3v4M3 5h4M6 17v4m-2-2h4m5-16l2.286 6.857L21 12l-5.714 2.143L13 21l-2.286-6.857L5 12l5.714-2.143L13 3z" />
              </svg>
            </span>
            <h1 class="text-2xl font-semibold text-gray-700 capitalize dark:text-white">Simple & clean designs</h1>
            <p class="text-gray-500 text-sm leading-7 dark:text-gray-300">Lorem ipsum dolor sit amet consectetur adipisicing elit. Provident ab nulla quod dignissimos vel non corrupti doloribus voluptatum eveniet</p>
          </div>
        </div>
      </div>
    </section>

    <div class="viewFooter mt-40 ClasAll">
      <div class="ClassName flex space-x-3 justify-center items-center">
        <pcIco />
        <h3 class="text-3xl xl:text-4xl dark:text-gray-200 font-semibold">Nusantara Developer</h3>
      </div>
      <p class="text-center desk_footer xl:w-1/3 mx-auto text-sm mt-5 leading-8 dark:text-gray-300">terimakasih telah berkunjung Di Website kami Nusantara Developer. Kami sangat senang Dengan Kehadiran Anda di website ini. semoga menginspirasikan Kalian Semua.</p>
      <footer class="md:flex md:items-center md:justify-between rounded-lg mt-16 p-4 md:p-6 xl:p-8">
        <ul class="flex group_cr items-center flex-wrap md:mb-0">
          <li><a href="#" class="text-sm font-normal dark:text-gray-200 hover:underline mr-4 md:mr-6">@copyright</a></li>
          <li><a href="#" class="text-sm font-normal dark:text-gray-200 hover:underline mr-4 md:mr-6">©️ZetDzak</a></li>
          <li><a href="#" class="text-sm font-normal dark:text-gray-200 hover:underline mr-4 md:mr-6">ebdtv4@gmail.com</a></li>
          <li><a href="#" class="text-sm font-normal dark:text-gray-200 hover:underline mr-4 md:mr-6">mhmdzakyadrhm@gmail.com</a></li>
          <li><a href="#" class="text-sm font-normal dark:text-gray-200 hover:underline">Contact</a></li>
        </ul>
        <div class="flex ico_footer space-x-6 justify-center">
          <facebookIco />
          <Insta />
          <a href="#" class="text-gray-500 hover:text-blue-500">
            <svg class="h-5 w-5" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true">
              <path d="M8.29 20.251c7.547 0 11.675-6.253 11.675-11.675 0-.178 0-.355-.012-.53A8.348 8.348 0 0022 5.92a8.19 8.19 0 01-2.357.646 4.118 4.118 0 001.804-2.27 8.224 8.224 0 01-2.605.996 4.107 4.107 0 00-6.993 3.743 11.65 11.65 0 01-8.457-4.287 4.106 4.106 0 001.27 5.477A4.072 4.072 0 012.8 9.713v.052a4.105 4.105 0 003.292 4.022 4.095 4.095 0 01-1.853.07 4.108 4.108 0 003.834 2.85A8.233 8.233 0 012 18.407a11.616 11.616 0 006.29 1.84"></path>
            </svg>
          </a>
          <GithubIco />
          <a href="#" class="text-gray-500 hover:text-blue-500">
            <svg class="h-5 w-5" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true">
              <path
                fill-rule="evenodd"
                d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10c5.51 0 10-4.48 10-10S17.51 2 12 2zm6.605 4.61a8.502 8.502 0 011.93 5.314c-.281-.054-3.101-.629-5.943-.271-.065-.141-.12-.293-.184-.445a25.416 25.416 0 00-.564-1.236c3.145-1.28 4.577-3.124 4.761-3.362zM12 3.475c2.17 0 4.154.813 5.662 2.148-.152.216-1.443 1.941-4.48 3.08-1.399-2.57-2.95-4.675-3.189-5A8.687 8.687 0 0112 3.475zm-3.633.803a53.896 53.896 0 013.167 4.935c-3.992 1.063-7.517 1.04-7.896 1.04a8.581 8.581 0 014.729-5.975zM3.453 12.01v-.26c.37.01 4.512.065 8.775-1.215.25.477.477.965.694 1.453-.109.033-.228.065-.336.098-4.404 1.42-6.747 5.303-6.942 5.629a8.522 8.522 0 01-2.19-5.705zM12 20.547a8.482 8.482 0 01-5.239-1.8c.152-.315 1.888-3.656 6.703-5.337.022-.01.033-.01.054-.022a35.318 35.318 0 011.823 6.475 8.4 8.4 0 01-3.341.684zm4.761-1.465c-.086-.52-.542-3.015-1.659-6.084 2.679-.423 5.022.271 5.314.369a8.468 8.468 0 01-3.655 5.715z"
                clip-rule="evenodd"></path>
            </svg>
          </a>
        </div>
      </footer>
    </div>
  </div>
</template>
