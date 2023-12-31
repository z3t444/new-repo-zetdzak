<script setup>
  // //css file import location
  import VSCode from "../components/icons/VSCode.vue"
  import "../assets/css/keyframes.css"
  import "../assets/css/responsive.css"
  import "../assets/css/shineText.css"
  import "../assets/css/rotateImg.css"

  // //import Ico location
  import Profile from "../components/icons/Profile.vue"
  import Clock from "../components/icons/Clock.vue"
  import htmlIco from "../components/icons/html.vue"
  import VueIco from "../components/icons/vueIco.vue"
  import SvelteIco from "../components/icons/svelteICo.vue"
  import ReactIco from "../components/icons/ReactIco.vue"
  import AngularIco from "../components/icons/AngularIco.vue"
  import TailwindIco from "../components/icons/tailwindIco.vue"
  import BootstrapIco from "../components/icons/bootstrapIco.vue"
  import ViteIco from "../components/icons/viteIco.vue"
  import NuxtIco from "../components/icons/nuxtIco.vue"
  import VuetifyIco from "../components/icons/vuetifyIco.vue"
  import PugIco from "../components/icons/pugIco.vue"
  import cssIco from "../components/icons/cssIco.vue"
  import jsIco from "../components/icons/jsIco.vue"
  import nestjsIco from "../components/icons/icoBackend/nestJsIco.vue"
  import expressjsIco from "../components/icons/icoBackend/expressjsIco.vue"
  import rubyIco from "../components/icons/icoBackend/rubyIco.vue"
  import springIco from "../components/icons/icoBackend/springIco.vue"
  import nextjsIco from "../components/icons/icoBackend/nextjsIco.vue"
  import hapijsIco from "../components/icons/icoBackend/hapijsIco.vue"
  import symfonyIco from "../components/icons/icoBackend/symfonyIco.vue"
  import laravelIco from "../components/icons/icoBackend/laravelIco.vue"
  import fastIco from "../components/icons/icoBackend/fastapiIco.vue"
  import djangoIco from "../components/icons/icoBackend/djangoIco.vue"
  import arrow from "../components/icons/arrow.vue"
  import Lightning from "../components/icons/lightning.vue"
  import chat from "../components/icons/chat.vue"
  import Insta from "../assets/ico/insta.vue"
  import GithubIco from "../assets/ico/githubIco.vue"
  import facebookIco from "../assets/ico/facebookIco.vue"
  import pcIco from "..//assets/ico/pcIco.vue"

  // //CONTENT import location
  import paralax1 from "../content/paralax1.vue"
  import paralax2 from "../content/paralax2.vue"
  import contentBlur from "../content/contentBlur.vue"
  import GalleryGrid from "../content/GalleryGrid.vue"
  import ImageGlobe from "../components/ImageGlobe.vue"
</script>

<template>
  <body class="dm_sans">
    <div class="ClassName">
      <div class="relative xl:container mx-auto">
        <div>
          <p class="sm:text-lg daily text-orange-400 text-center md:pt-12 lg:pt-20 lg:text-start dark:text-orange-400 font-semibold lg:w-11/12">Daily Us Collaboration</p>
        </div>
        <h1 class="glow_text sm:mx-auto font-black mt-7 text-blue-900 text-4xl text-center sm:text-5xl md:text-6xl lg:w-auto lg:text-left xl:text-8xl dark:text-white animate-spin-letters">
          We Are <br class="lg:block hidden" />
          <span class="relative text-transparent bg-clip-text bg-gradient-to-r from-blue-600 to-cyan-500 dark:from-blue-400 dark:to-cyan-300">Web Developer</span>.
        </h1>

        <div class="md:flex col_content lg:flex items-center justify-center">
          <div class="sm:mt-10 md:mt-10 sm:w-10/12 md:w-2/3 lg:ml-0 sm:mx-auto text-center lg:text-left lg:mr-auto lg:w-7/12">
            <p class="max_desk text-gray-700 dark:text-gray-300 lg:w-11/12">Daily life with the best collaboration between us Frontend and Backend. from all Project Creation, Web Profile, Corporate Web, Marketplace, Parallax Web design, and agency web design. Our web is a Profile Website</p>

            <div class="ico_pad grid grid-cols-3 space-x-4 md:space-x-6 mt-10 md:flex md:justify-center lg:justify-start">
              <a aria-label="add to slack" href="#" target="_blank" class="slack p-4 border border-gray-200 dark:bg-gray-800 dark:border-gray-700 rounded-full duration-300 hover:border-cyan-400 hover:shadow-lg hover:shadow-cyan-600/20 dark:hover:border-cyan-300/30">
                <div class="flex justify-center space-x-3">
                  <img class="w-6 h-6" src="https://tailus.io/sources/blocks/tech-startup/preview/images/slack.png" alt="slack logo" loading="lazy" width="128" height="128" />
                  <span class="hidden font-medium md:block dark:text-gray-200">Slack</span>
                </div>
              </a>
              <a aria-label="add to chat" href="#" target="_blank" class="google_chat p-4 border border-gray-200 dark:bg-gray-800 dark:border-gray-700 rounded-full duration-300 hover:border-green-400 hover:shadow-lg hover:shadow-lime-600/20 dark:hover:border-green-300/30">
                <div class="flex justify-center space-x-4">
                  <img class="w-6 h-6" src="https://tailus.io/sources/blocks/tech-startup/preview/images/chat.png" alt="chat logo" loading="lazy" width="128" height="128" />
                  <span class="hidden font-medium md:block dark:text-white">Google Chat</span>
                </div>
              </a>
              <a aria-label="add to zoom" href="#" target="_blank" class="p-4 border border-gray-200 dark:bg-gray-800 dark:border-gray-700 rounded-full duration-300 hover:border-blue-400 hover:shadow-lg hover:shadow-blue-600/20 dark:hover:border-blue-300/30">
                <div class="flex justify-center space-x-4">
                  <img class="w-6 h-6" src="https://tailus.io/sources/blocks/tech-startup/preview/images/zoom.png" alt="chat logo" loading="lazy" width="128" height="128" />
                  <span class="hidden font-medium md:block dark:text-white">Zoom</span>
                </div>
              </a>
            </div>

            <div class="sugaris_items text-sm dark:text-gray-300 mt-12">
              🔥🌟
              <span>Other integrations :</span>
              <a href="#" class="font-semibold text-gray-700 dark:text-gray-200"><a href="https://discord.com/" target="_blank">Discord,</a> </a>
              <a href="#" class="font-semibold text-gray-700 dark:text-gray-200"><a href="https://www.instagram.com/zzz_3t44" target="_blank"></a></a>
            </div>

            <div class="p-3 support_brand rounded-2xl glass_background flex items-center gap-6 lg:gap-12 lg:mt-5 justify-between grayscale lg:w-2/3">
              <a href="#" target="_blank"><VSCode /></a>
              <a href="#" target="_blank"> <img src="https://tailus.io/sources/blocks/tech-startup/preview/images/clients/ge.svg" class="h-8 sm:h-10 w-auto lg:h-12" alt="" /></a>
              <a href="#" target="_blank"> <img src="https://tailus.io/sources/blocks/tech-startup/preview/images/clients/coty.svg" class="h-8 sm:h-10 w-auto lg:h-12" alt="" /></a>
              <a href="#" target="_blank"> <img src="https://tailus.io/sources/blocks/tech-startup/preview/images/clients/microsoft.svg" class="h-8 sm:h-10 w-auto lg:h-12" alt="" /></a>
            </div>
          </div>

          <!-- //image header// -->
          <div class="ClassName globe_mod">
            <ImageGlobe />
          </div>
        </div>
      </div>
    </div>
  </body>

  <!-- content feature -->
  <div class="container mx-auto p-4 mt-48 dm_sans">
    <p class="text-center zetdzak_name font-medium dark:text-gray-200">ZetDzak</p>
    <h3 class="text-center gradient_nusantara dark:text-gray-200 text-6xl mt-3 font-normal">Leader of <span class="nusantara_text font-semibold bg-gradient-to-r from-red-500 to-blue-400 dark:bg-gradient-to-r dark:from-red-500 dark:to-white bg-clip-text text-transparent">Nusantara</span> Programmer</h3>
    <p class="ClassName_desk_nusantara text-center text-md mt-6 leading-8 dark:text-gray-200">
      Lorem ipsum dolor sit amet consectetur adipisicing elit. <br />
      Error esse harum quaerat ipsa. Autem
    </p>
    <div class="grid grid-cols-1 sm:grid-cols-2 mt-16 md:grid-cols-3 gap-4">
      <!-- Box 1 -->
      <div class="p-4 shadow-md text-center dark:text-gray-200 text-lg">
        <h2 class="text-2xl font-semibold mb-2">😇Box 1</h2>
        <p class="text-sm mt-5">Lorem ipsum dolor sit amet, consectetur</p>
      </div>

      <!-- Box 2 -->
      <div class="p-4 shadow-md text-center dark:text-gray-200 text-lg">
        <h2 class="text-2xl font-semibold mb-2">🧐 Box 2</h2>
        <p class="text-sm mt-5">Lorem ipsum dolor sit amet, consectetur</p>
      </div>

      <!-- Box 3 -->
      <div class="p-4 shadow-md text-center dark:text-gray-200 text-lg">
        <h2 class="text-2xl font-semibold mb-2">🤓 Box 3</h2>
        <p class="text-sm mt-5">Lorem ipsum dolor sit amet, consectetur</p>
      </div>
    </div>
    <div class="text-center mt-12">
      <a class="dark:text-gray-200 p-4 rounded-3xl font-medium hover:bg-blue-800 duration-100 bg-blue-500" href="#">Join Community</a>
      <a href="#"></a>
    </div>
  </div>

  <div class="flex flex-col dm_sans md:flex-row mt-60 justify-around space-x-2 items-center padding_hero p-16 border border-gray-200 dark:border-gray-800 rounded-3xl" style="background-color: #1c1c2e">
    <div class="galleryGrid">
      <GalleryGrid />
    </div>
    <div class="content_Desk md:w-1/2">
      <h3 class="ClassName settings_text text-hero text-4xl mt-2 font-medium dark:text-gray-200"><span class="ClassText_friends font-bold text-red-600">Friends </span>Web Developer From Yogyakarta</h3>
      <p class="dark:text-gray-200 mt-7 desk_text_settings leading-8 text-gray-800">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Autem, est omnis. Culpa vitae facilis suscipit, natus voluptatibus itaque fugit officiis dolores aut dolor enim sint temporibus corporis ducimus at inventore?</p>
      <div class="button_in_hero dark:text-gray-200 mt-10 flex justify-start items-center text-center space-x-5 p-5">
        <a href="https://mhm-dzaky.vercel.app/" class="p-3 bg-blue-500 hover:bg-blue-600 text-white duration-100 w-28 rounded-full" target="_blank">Dzaky </a>
        <a href="https://zeeta.my.id" class="p-3 bg-blue-500 hover:bg-blue-600 w-28 rounded-full text-white dark:hover:bg-blue-600 duration-100" target="_blank">Zeeta </a>
        <p class="light_p font-semibold">Visite this SITE!</p>
      </div>
    </div>
  </div>

  <div class="mt-36 introduction_card">
    <div class="dm_sans">
      <h2 class="text-4xl text_love font-medium dark:text-gray-200">Enterprise developers <span class="love">❤️</span> <span class="font-bold">ZetDzak</span></h2>
      <p class="mt-6 text_desk_love dark:text-gray-200 text-md">
        Features of Our Performance in <br />
        Website Development
      </p>
    </div>
  </div>

  <div class="flex flex-wrap dm_sans mt-10 text-black dark:text-white">
    <div class="w-full sm:w-1/2 md:w-1/4 p-3">
      <div class="border1 h-72 border hover:scale-110 duration-150 dark:border-gray-800 rounded-3xl p-5 shadow-md flex-col text-start items-center justify-between hover:border-cyan-400 hover:shadow-lg hover:shadow-cyan-600/20 dark:hover:border-cyan-300/30" style="background-color: #1c1c2e">
        <Profile />
        <h3 class="text-2xl font-semibold mt-7">Be friendly</h3>
        <p class="mt-5 dark:text-gray-300">We are very friendly in every way, such as collaboration and Q&A.</p>
      </div>
    </div>

    <div class="w-full sm:w-1/2 md:w-1/4 p-3">
      <div class="border2 h-72 rounded-3xl hadow-md flex items-center justify-center">
        <div class="bord h-72 border hover:scale-110 duration-150 dark:border-gray-800 rounded-3xl p-5 shadow-md flex-col text-start items-center justify-center hover:border-green-400 hover:shadow-lg hover:shadow-lime-600/20 dark:hover:border-green-300/30" style="background-color: #1c1c2e">
          <Clock />
          <h3 class="text-2xl font-semibold mt-7">24/7 Hours</h3>
          <p class="mt-5 dark:text-gray-300">we work in a 24-hour week. to improve performance and flight hours for us developers.</p>
        </div>
      </div>
    </div>

    <div class="w-full sm:w-1/2 md:w-1/4 p-3">
      <div class="border3 h-72 rounded-3xl flex items-center justify-center">
        <div class="bord h-72 border hover:scale-110 duration-150 dark:border-gray-800 rounded-3xl p-5 shadow-md flex-col text-start items-center justify-center hover:border-yellow-400 hover:shadow-lg hover:shadow-yellow-600/20 dark:hover:border-yellow-300/30" style="background-color: #1c1c2e">
          <Lightning />
          <h3 class="text-2xl font-semibold mt-7">Faster</h3>
          <p class="mt-5 dark:text-gray-300">we are fast in working on requests from clients. because we have been trained to respond quickly</p>
        </div>
      </div>
    </div>

    <div class="w-full sm:w-1/2 md:w-1/4 p-3">
      <div class="border4 h-72 rounded-3xl flex items-center justify-center">
        <div class="bord h-72 border hover:scale-110 duration-150 dark:border-gray-800 rounded-3xl p-5 shadow-md flex-col text-start items-center justify-center hover:border-green-400 hover:shadow-lg hover:shadow-green-600/20 dark:hover:border-green-300/30" style="background-color: #1c1c2e">
          <chat />
          <h3 class="text-2xl font-semibold mt-7">Message</h3>
          <p class="mt-5 dark:text-gray-300">we will always answer questions or statements from others if we really need to communicate.</p>
        </div>
      </div>
    </div>
  </div>

  <div>
    <div class="mt-60 dm_sans">
      <div class="..">
        <p class="skill text-4xl font-normal dark:text-gray-200">Web <span class="dev_txt font-semibold">dev</span> framework <span class="skills_txt font-semibold">skills</span> that we <span class="master_txt font-semibold">master</span></p>
      </div>
    </div>
    <div class="mt-16 bg_marquee rounded-3xl" style="background-color: #1c1c2e">
      <div>
        <!-- //marquee icon frontend// -->
        <marquee class="marquee1 rounded-3xl" behavior="" direction="" scrollamount="15">
          <div class="flex items-center space-x-6 dark:text-gray-200">
            <div class="ico_framework border rounded-full border-gray-300 dark:bg-gray-900 dark:border-gray-900"><htmlIco /></div>
            <div class="ico_framework border rounded-full border-gray-300 dark:bg-gray-900 dark:border-gray-900"><VueIco /></div>
            <div class="ico_framework border rounded-full border-gray-300 dark:bg-gray-900 dark:border-gray-900"><SvelteIco /></div>
            <div class="ico_framework border rounded-full border-gray-300 dark:bg-gray-900 dark:border-gray-900"><ReactIco /></div>
            <div class="ico_framework border rounded-full border-gray-300 dark:bg-gray-900 dark:border-gray-900"><AngularIco /></div>
            <div class="ico_framework border rounded-full border-gray-300 dark:bg-gray-900 dark:border-gray-900"><TailwindIco /></div>
            <div class="ico_framework border rounded-full border-gray-300 dark:bg-gray-900 dark:border-gray-900"><BootstrapIco /></div>
            <div class="ico_framework border rounded-full border-gray-300 dark:bg-gray-900 dark:border-gray-900"><ViteIco /></div>
            <div class="ico_framework border rounded-full border-gray-300 dark:bg-gray-900 dark:border-gray-900"><NuxtIco /></div>
            <div class="ico_framework border rounded-full border-gray-300 dark:bg-gray-900 dark:border-gray-900"><VuetifyIco /></div>
            <div class="ico_framework border rounded-full border-gray-300 dark:bg-gray-900 dark:border-gray-900"><PugIco /></div>
            <div class="ico_framework border rounded-full border-gray-300 dark:bg-gray-900 dark:border-gray-900"><cssIco /></div>
            <div class="ico_framework border rounded-full border-gray-300 dark:bg-gray-900 dark:border-gray-900"><jsIco /></div>
          </div>
        </marquee>

        <!-- //marquee icon backend// -->
        <marquee class="marquee2 mt-5 rounded-3xl" behavior="" direction="right" scrollamount="10">
          <div class="flex items-center space-x-6 dark:text-gray-200">
            <div class="ico_framework border rounded-full border-gray-300 dark:bg-gray-900 dark:border-gray-900"><nestjsIco /></div>
            <div class="ico_framework border rounded-full border-gray-300 dark:bg-gray-900 dark:border-gray-900"><expressjsIco /></div>
            <div class="ico_framework border rounded-full border-gray-300 dark:bg-gray-900 dark:border-gray-900"><rubyIco /></div>
            <div class="ico_framework border rounded-full border-gray-300 dark:bg-gray-900 dark:border-gray-900"><springIco /></div>
            <div class="ico_framework border rounded-full border-gray-300 dark:bg-gray-900 dark:border-gray-900"><nextjsIco /></div>
            <div class="ico_framework border rounded-full border-gray-300 dark:bg-gray-900 dark:border-gray-900"><hapijsIco /></div>
            <div class="ico_framework border rounded-full border-gray-300 dark:bg-gray-900 dark:border-gray-900"><symfonyIco /></div>
            <div class="ico_framework border rounded-full border-gray-300 dark:bg-gray-900 dark:border-gray-900"><laravelIco /></div>
            <div class="ico_framework border rounded-full border-gray-300 dark:bg-gray-900 dark:border-gray-900"><fastIco /></div>
            <div class="ico_framework border rounded-full border-gray-300 dark:bg-gray-900 dark:border-gray-900"><djangoIco /></div>
          </div>
        </marquee>
      </div>

      <div class="dm_sans mt-20 flex items-center desk_gear_emoji justify-between">
        <div>
          <h2 class="text-3xl dark:text-gray-300 font-semibold">Awesome Framework Use <span class="gear_emoji">⚙️</span></h2>
          <p class="dark:text-gray-300 mt-5 xl:w-3/4">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quia, molestiae at. In hic nisi eveniet quia alias dicta pariatur autem delectus nesciunt omnis sit voluptatem corporis quisquam, eaque, laborum rerum.</p>
        </div>
        <div class="btn-about flex space-x-3">
          <a href="#" class="text-black dark:text-white text-md font-medium w-32 text-center bg-cyan-300 hover:bg-cyan-500 duration-150 dark:bg-cyan-500 hover:dark:bg-cyan-600 p-5 pt-3 pb-3 rounded-full link_about" target="_blank">About Me</a>
          <arrow />
        </div>
      </div>
    </div>
  </div>

  <!-- //content profile// -->
  <div class="mt-5">
    <div class="flex flex_responsive_parallax justify-center">
      <div class="p-4 m-2 parallax1 bg-gray-100 rounded-3xl sm:w-1/2" style="background-color: #1c1c2e">
        <paralax1 />
      </div>
      <div class="p-4 m-2 parallax2 bg-gray-100 rounded-3xl sm:w-1/2 lg:w-full" style="background-color: #1c1c2e">
        <paralax2 />
      </div>
    </div>

    <div class="content_image_blur mt-36">
      <contentBlur />
    </div>
    <div class="viewFooter mt-40 dm_sans">
      <div class="ClassName flex space-x-3 justify-center items-center">
        <pcIco />
        <h3 class="text-3xl font-semibold dark:text-gray-200">ZetDzak</h3>
      </div>
      <p class="text-center desk_footer mt-5 dark:text-gray-300">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Doloribus velit enim eligendi vero <br />
        Placeat voluptates ad suscipit, hic officiis vel sed eligendi qui, dolorum rerum
      </p>

      <footer class="md:flex md:items-center md:justify-between rounded-lg mt-16 p-4 md:p-6 xl:p-8">
        <ul class="flex group_cr items-center flex-wrap md:mb-0">
          <li><a href="#" class="text-sm font-normal dark:text-gray-200 hover:underline mr-4 md:mr-6">@copyright</a></li>
          <li><a href="#" class="text-sm font-normal dark:text-gray-200 hover:underline mr-4 md:mr-6">©️ZetDzak</a></li>
          <li><a href="#" class="text-sm font-normal dark:text-gray-200 hover:underline mr-4 md:mr-6">ebdtv4@gmail.com</a></li>
          <li><a href="#" class="text-sm font-normal dark:text-gray-200 hover:underline mr-4 md:mr-6">mhmdzakyadrhm@gmail.com</a></li>
          <li><a href="#" class="text-sm font-normal dark:text-gray-200 hover:underline">Contact</a></li>
        </ul>
        <div class="flex space-x-6 ico_footer justify-center">
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

<style scoped>
  @import url("https://fonts.googleapis.com/css2?family=DM+Sans:ital,opsz,wght@0,9..40,300;0,9..40,400;0,9..set40,500;0,9..40,600;0,9..40,700;0,9..40,800;0,9..40,900;0,9..40,1000;1,9..40,300;1,9..40,400;1,9..40,500;1,9..40,600;1,9..40,700;1,9..40,800;1,9..40,900;1,9..40,1000&display=swap");
  @import url("https://fonts.googleapis.com/css2?family=DM+Sans:ital,opsz,wght@0,9..40,300;0,9..40,400;0,9..40,500;0,9..40,600;0,9..40,700;0,9..40,800;0,9..40,900;0,9..40,1000;1,9..40,300;1,9..40,400;1,9..40,500;1,9..40,600;1,9..40,700;1,9..40,800;1,9..40,900;1,9..40,1000&display=swap");

  .header_image {
    animation: wave 5s infinite;
    top: 44px;
  }
  .glow_text {
    animation: neon 10s ease-in-out infinite alternate;
  }
  .allert {
    font-size: 13px;
  }
  .max_desk {
    max-width: 630px;
    font-size: 17px;
    line-height: 33px;
  }
  .max_paragraph {
    max-width: 680px;
  }
  /* demo */
  .dm_sans {
    font-family: "DM Sans", sans-serif;
  }
  .love {
    text-shadow: 0px 0px 30px red;
  }
  .light_lamp {
    text-shadow: 0px 0px 30px yellow;
  }

  .ico_framework {
    transition: all 0.2s ease-out;
  }
  .ico_framework:hover {
    scale: 1.1;
  }
  .bg_marquee {
    padding: 50px;
  }
  .dev_txt {
    color: #26d37c;
    text-shadow: 0px 0px 30px #26d37c;
  }
  .skills_txt {
    color: #47ebeb;
    text-shadow: 0px 0px 30px #47ebeb;
  }
  .master_txt {
    color: #f2494a;
    text-shadow: 0px 0px 30px #f2494a;
  }
  .gear_emoji {
    text-shadow: 0px 0px 40px;
  }
  .for_bg_img {
    background-color: red;
    height: 350px;
    width: 250px;
  }
  .image_ss {
    width: 700px;
  }

  .ClassText_friends {
    text-shadow: 0px 0px 30px red;
  }

  .settings_text {
    line-height: 55px;
    max-width: 600px;
  }

  .light_p {
    text-shadow: 0px 0px 30px white;
  }
</style>
