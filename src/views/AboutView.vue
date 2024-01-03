<script setup>
  import Graph from "../components/Graph.vue"
  import "../assets/css/keyframes.css"
  import "../assets/css/responsive.css"
  import "../assets/css/shineText.css"

  // import Ico
  import GithubIco from "../assets/ico/githubIco.vue"
  import Github from "../assets/ico/github.vue"
  import facebookIco from "../assets/ico/facebookIco.vue"
  import Insta from "../assets/ico/insta.vue"
  import pcIco from "../assets/ico/pcIco.vue"
  import discordIco from "../assets/ico/discordIco.vue"
  import Discord from "../assets/ico/discord.vue"
  import Reddit from "../assets/ico/reddit.vue"
  import Zoom from "../assets/ico/zoom.vue"
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

    <div class="flex hero_about flex-col justify-between p-16 rounded-3xl items-center sm:flex-row mt-20 gap-10" style="background-color: #1c1c2e">
      <div class="p-4 w-full sm:w-1/2 rounded-2xl">
        <div class="for_import">
          <Graph />
        </div>
      </div>
      <div class="p-1 w-full sm:w-1/2">
        <p class="text-orange-400">Master of Management System</p>
        <h3 class="text-5xl font-medium mt-5 manage_system_security leading-snug">Manage All system and Data Security</h3>
        <p class="dark:text-gray-300 mt-8 leading-8">
          Lorem ipsum dolor sit amet consectetur, adipisicing elit. Voluptatum necessitatibus <br />
          beatae perspiciatis porro cumque tempore, ipsa similique omnis voluptates esse!
        </p>
        <p class="dark:text-gray-300 mt-7 leading-8">
          Lorem ipsum dolor sit, amet consectetur <br />
          adipisicing elit.
        </p>
        <div class="flex items-center flex-col sm:flex-row md:flex-col lg:flex-row mt-10 gap-10">
          <a href="#" class="bg-blue-500 dark:text-gray-200 hover:bg-transparent hover:border text-black hover:border-blue-400 text-center w-36 duration-100 p-4 rounded-full">Read More</a>
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
    </div>

    <div class="ClassName mt-24 grid_github p-9 rounded-3xl">
      <div class="flex flex-wrap items-center justify-between">
        <!-- Box Kedua dengan 4 Grid Box -->
        <div class="w-full md:w-1/2 p-4">
          <div class="p-1 rounded center_txt">
            <h4 class="text-3xl font-medium leading-snug">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Iure perferendis!</h4>
            <p class="mt-10 dark:text-gray-300">Lorem ipsum dolor sit amet consectetur adipisicing elit. Vitae quis animi, reiciendis maxime incidunt neque, perferendis voluptatum veritatis cum earum debitis harum obcaecati voluptatem magni facilis nisi minus aspernatur repellendus?</p>
          </div>
        </div>
        <div class="w-full md:w-1/2 p-4 margin_state">
          <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-2 gap-4">
            <div class="grid grid-cols-1 gap-6">
              <div class="p-6 rounded-3xl flex space-x-3 dark:border dark:border-gray-800 hover:scale-105 duration-100" style="background-color: #1c1c2e">
                <Discord />
                <div>
                  <h4 class="dark:text-gray-300">View Of</h4>
                  <h4 class="dark:text-gray-200 font-medium text-lg mt-2">Repo Github</h4>
                </div>
              </div>
              <div class="p-6 rounded-3xl flex space-x-3 dark:border dark:border-gray-800 hover:scale-105 duration-100" style="background-color: #1c1c2e">
                <Github />
                <div>
                  <h4 class="dark:text-gray-300">View Of</h4>
                  <h4 class="dark:text-gray-200 font-medium text-lg mt-2">Repo Github</h4>
                </div>
              </div>
            </div>
            <div class="grid grid-cols-1 gap-6">
              <div class="p-6 rounded-3xl flex space-x-3 dark:border dark:border-gray-800 hover:scale-105 duration-100" style="background-color: #1c1c2e">
                <Reddit />
                <div>
                  <h4 class="dark:text-gray-300">View Of</h4>
                  <h4 class="dark:text-gray-200 font-medium text-lg mt-2">Repo Github</h4>
                </div>
              </div>
              <div class="p-6 rounded-3xl flex space-x-3 dark:border dark:border-gray-800 hover:scale-105 duration-100" style="background-color: #1c1c2e">
                <Zoom />
                <div>
                  <h4 class="dark:text-gray-300">View Of</h4>
                  <h4 class="dark:text-gray-200 font-medium text-lg mt-2">Repo Github</h4>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <section>
      <div class="other_gallery_card mt-44">
        <h2 class="text-3xl text-center font-medium">Our main Team</h2>
        <div class="flex flex-wrap gap-10 mx-auto justify-center mt-10 rounded-3xl">
          <div class="w-full sm:w-10 md:w-32 lg:w-40 xl:w-64 p-4 duration-100">
            <img class="rounded-full asset_profile" src="../assets/img/zet.jpg" alt="" />
            <div class="text-center mt-5">
              <h3 class="text-2xl font-medium">Im Zet</h3>
              <p class="mt-3 text-sm dark:text-gray-400">Frontend Developer</p>
            </div>
          </div>
          <div class="w-full sm:w-10 md:w-32 lg:w-40 xl:w-64 p-4 duration-100">
            <img class="rounded-full asset_profile" src="../assets/img/akaksayangg.png" alt="" />
            <div class="text-center mt-5">
              <h3 class="text-2xl font-medium">Im Zet</h3>
              <p class="mt-3 text-sm dark:text-gray-400">Frontend Developer</p>
            </div>
          </div>
          <div class="w-full sm:w-10 md:w-32 lg:w-40 xl:w-64 p-4 duration-100">
            <img class="rounded-full asset_profile" src="../assets/img/relpicture.jpg" alt="" />
            <div class="text-center mt-5">
              <h3 class="text-2xl font-medium">Im Zet</h3>
              <p class="mt-3 text-sm dark:text-gray-400">Frontend Developer</p>
            </div>
          </div>
          <div class="w-full sm:w-10 md:w-32 lg:w-40 xl:w-64 p-4 duration-100">
            <img class="rounded-full asset_profile" src="../assets/img/akaksayangg.png" alt="" />
            <div class="text-center mt-5">
              <h3 class="text-2xl font-medium">Im Zet</h3>
              <p class="mt-3 text-sm dark:text-gray-400">Frontend Developer</p>
            </div>
          </div>
        </div>
        <div class="flex flex-wrap mx-auto gap-10 justify-center mt-20 rounded-3xl">
          <div class="w-full sm:w-10 md:w-32 lg:w-40 xl:w-64 p-4 duration-100">
            <img class="rounded-full asset_profile" src="../assets/img/zet.jpg" alt="" />
            <div class="text-center mt-5">
              <h3 class="text-2xl font-medium">Im Zet</h3>
              <p class="mt-3 text-sm dark:text-gray-400">Frontend Developer</p>
            </div>
          </div>
          <div class="w-full sm:w-10 md:w-32 lg:w-40 xl:w-64 p-4 duration-100">
            <img class="rounded-full asset_profile" src="../assets/img/akaksayangg.png" alt="" />
            <div class="text-center mt-5">
              <h3 class="text-2xl font-medium">Im Zet</h3>
              <p class="mt-3 text-sm dark:text-gray-400">Frontend Developer</p>
            </div>
          </div>
          <div class="w-full sm:w-10 md:w-32 lg:w-40 xl:w-64 p-4 duration-100">
            <img class="rounded-full asset_profile" src="../assets/img/zet.jpg" alt="" />
            <div class="text-center mt-5">
              <h3 class="text-2xl font-medium">Im Zet</h3>
              <p class="mt-3 text-sm dark:text-gray-400">Frontend Developer</p>
            </div>
          </div>
          <div class="w-full sm:w-10 md:w-32 lg:w-40 xl:w-64 p-4 duration-100">
            <img class="rounded-full asset_profile" src="../assets/img/akaksayangg.png" alt="" />
            <div class="text-center mt-5">
              <h3 class="text-2xl font-medium">Im Zet</h3>
              <p class="mt-3 text-sm dark:text-gray-400">Frontend Developer</p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <div class="ClassName maintxt_for_dc flex items-center justify-between p-10" style="margin-top: 750px">
      <h3 class="text-4xl font-normal"><span class="text-sky-400 font-semibold people_txt_glow">People</span> constribution on <span class="font-semibold discord_txt_glow text-purple-700">Discord</span> server</h3>
      <div class="ClassName flex discord_and_button items-center space-x-2 p-3 border border-gray-900 rounded-full bg-gray-800 hover:shadow-2xl duration-100 hover:scale-105">
        <discordIco />
        <h4 class="font-medium">Join</h4>
      </div>
    </div>
    <section class="p-2 margin_state dark:text-gray-200 rounded-3xl" style="background-color: #1c1c2e">
      <div class="flex coloumn_rate items-center p-10 rounded-3xl">
        <div class="ClassName img">
          <img src="../assets/img/rplcoding.jpg" class="rounded-3xl hover:scale-105 duration-100" width="650px" alt="" />
        </div>
        <div class="container_rate mx-auto grid justify-center grid-cols-2 text-center lg:grid-cols-3">
          <div class="flex flex-col justify-start m-2 lg:m-6 dark:shadow-2xl hover:scale-105 duration-100">
            <p class="text-4xl font-bold leadi lg:text-6xl">50+</p>
            <p class="text-sm sm:text-base mt-5">Clients</p>
          </div>
          <div class="flex flex-col justify-start m-2 lg:m-6 dark:shadow-2xl hover:scale-105 duration-100">
            <p class="text-4xl font-bold leadi lg:text-6xl">89K</p>
            <p class="text-sm sm:text-base mt-5">Followers on social media</p>
          </div>
          <div class="flex flex-col justify-start m-2 lg:m-6 dark:shadow-2xl hover:scale-105 duration-100">
            <p class="text-4xl font-bold leadi lg:text-6xl">3</p>
            <p class="text-sm sm:text-base mt-5">Published books</p>
          </div>
          <div class="flex flex-col justify-start m-2 lg:m-6 dark:shadow-2xl hover:scale-105 duration-100">
            <p class="text-4xl font-bold leadi lg:text-6xl">8</p>
            <p class="text-sm sm:text-base mt-5">TED talks</p>
          </div>
          <div class="flex flex-col justify-start m-2 lg:m-6 dark:shadow-2xl hover:scale-105 duration-100">
            <p class="text-4xl font-bold leadi lg:text-6xl">22</p>
            <p class="text-sm sm:text-base mt-5">Years of experience</p>
          </div>
          <div class="flex flex-col justify-start m-2 lg:m-6 dark:shadow-2xl hover:scale-105 duration-100">
            <p class="text-4xl font-bold leadi lg:text-6xl">10+</p>
            <p class="text-sm sm:text-base mt-5">Workshops</p>
          </div>
        </div>
      </div>
    </section>

    <section class="dark:text-gray-200 mt-24">
      <div class="container px-5 mx-auto">
        <div class="flex flex-col text-start w-full mb-20">
          <h1 class="sm:text-4xl text-2xl font-medium mb-4 dark:text-gray-200">Our Team</h1>
          <p class="lg:w-2/6 mt-5 dark:text-gray-300 leading-relaxed text-base">Whatever cardigan tote bag tumblr hexagon brooklyn asymmetrical gentrify, subway tile poke farm-to-table. Franzen you probably haven't heard of them.</p>
        </div>
        <div class="flex flex-wrap -m-2">
          <div class="p-2 lg:w-1/3 md:w-1/2 w-full">
            <div class="h-full flex items-center dark:border-gray-800 hover:bg-transparent border p-4 rounded-2xl hover:scale-105 duration-100" style="background-color: #1c1c2e">
              <img alt="team" class="w-16 h-16 bg-gray-100 object-cover object-center flex-shrink-0 rounded-full mr-4" src="../assets/img/akaksayangg.png" />
              <div class="flex-grow">
                <h2 class="dark:text-gray-200 title-font font-medium">Holden Caulfield</h2>
                <p class="text-gray-400">UI Designer</p>
              </div>
            </div>
          </div>
          <div class="p-2 lg:w-1/3 md:w-1/2 w-full">
            <div class="h-full flex items-center dark:border-gray-800 hover:bg-transparent border p-4 rounded-2xl hover:scale-105 duration-100" style="background-color: #1c1c2e">
              <img alt="team" class="w-16 h-16 bg-gray-100 object-cover object-center flex-shrink-0 rounded-full mr-4" src="../assets/img/akaksayangg.png" />
              <div class="flex-grow">
                <h2 class="dark:text-gray-200 title-font font-medium">Henry Letham</h2>
                <p class="text-gray-400">CTO</p>
              </div>
            </div>
          </div>
          <div class="p-2 lg:w-1/3 md:w-1/2 w-full">
            <div class="h-full flex items-center dark:border-gray-800 hover:bg-transparent border p-4 rounded-2xl hover:scale-105 duration-100" style="background-color: #1c1c2e">
              <img alt="team" class="w-16 h-16 bg-gray-100 object-cover object-center flex-shrink-0 rounded-full mr-4" src="../assets/img/akaksayangg.png" />
              <div class="flex-grow">
                <h2 class="dark:text-gray-200 title-font font-medium">Oskar Blinde</h2>
                <p class="text-gray-400">Founder</p>
              </div>
            </div>
          </div>
          <div class="p-2 lg:w-1/3 md:w-1/2 w-full">
            <div class="h-full flex items-center dark:border-gray-800 hover:bg-transparent border p-4 rounded-2xl hover:scale-105 duration-100" style="background-color: #1c1c2e">
              <img alt="team" class="w-16 h-16 bg-gray-100 object-cover object-center flex-shrink-0 rounded-full mr-4" src="../assets/img/akaksayangg.png" />
              <div class="flex-grow">
                <h2 class="dark:text-gray-200 title-font font-medium">John Doe</h2>
                <p class="text-gray-400">DevOps</p>
              </div>
            </div>
          </div>
          <div class="p-2 lg:w-1/3 md:w-1/2 w-full">
            <div class="h-full flex items-center dark:border-gray-800 hover:bg-transparent border p-4 rounded-2xl hover:scale-105 duration-100" style="background-color: #1c1c2e">
              <img alt="team" class="w-16 h-16 bg-gray-100 object-cover object-center flex-shrink-0 rounded-full mr-4" src="../assets/img/akaksayangg.png" />
              <div class="flex-grow">
                <h2 class="dark:text-gray-200 title-font font-medium">Martin Eden</h2>
                <p class="text-gray-400">Software Engineer</p>
              </div>
            </div>
          </div>
          <div class="p-2 lg:w-1/3 md:w-1/2 w-full">
            <div class="h-full flex items-center dark:border-gray-800 hover:bg-transparent border p-4 rounded-2xl hover:scale-105 duration-100" style="background-color: #1c1c2e">
              <img alt="team" class="w-16 h-16 bg-gray-100 object-cover object-center flex-shrink-0 rounded-full mr-4" src="../assets/img/akaksayangg.png" />
              <div class="flex-grow">
                <h2 class="dark:text-gray-200 title-font font-medium">Boris Kitua</h2>
                <p class="text-gray-400">UX Researcher</p>
              </div>
            </div>
          </div>
          <div class="p-2 lg:w-1/3 md:w-1/2 w-full">
            <div class="h-full flex items-center dark:border-gray-800 hover:bg-transparent border p-4 rounded-2xl hover:scale-105 duration-100" style="background-color: #1c1c2e">
              <img alt="team" class="w-16 h-16 bg-gray-100 object-cover object-center flex-shrink-0 rounded-full mr-4" src="../assets/img/akaksayangg.png" />
              <div class="flex-grow">
                <h2 class="dark:text-gray-200 title-font font-medium">Atticus Finch</h2>
                <p class="text-gray-400">QA Engineer</p>
              </div>
            </div>
          </div>
          <div class="p-2 lg:w-1/3 md:w-1/2 w-full">
            <div class="h-full flex items-center dark:border-gray-800 hover:bg-transparent border p-4 rounded-2xl hover:scale-105 duration-100" style="background-color: #1c1c2e">
              <img alt="team" class="w-16 h-16 bg-gray-100 object-cover object-center flex-shrink-0 rounded-full mr-4" src="../assets/img/akaksayangg.png" />
              <div class="flex-grow">
                <h2 class="dark:text-gray-200 title-font font-medium">Alper Kamu</h2>
                <p class="text-gray-400">System</p>
              </div>
            </div>
          </div>
          <div class="p-2 lg:w-1/3 md:w-1/2 w-full">
            <div class="h-full flex items-center dark:border-gray-800 hover:bg-transparent border p-4 rounded-2xl hover:scale-105 duration-100" style="background-color: #1c1c2e">
              <img alt="team" class="w-16 h-16 bg-gray-100 object-cover object-center flex-shrink-0 rounded-full mr-4" src="../assets/img/akaksayangg.png" />
              <div class="flex-grow">
                <h2 class="dark:text-gray-200 title-font font-medium">Rodrigo Monchi</h2>
                <p class="text-gray-500">Product Manager</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <div class="viewFooter mt-40 dm_sans">
      <div class="ClassName flex space-x-3 justify-center items-center">
        <pcIco />
        <h3 class="text-4xl font-semibold">ZetDzak</h3>
      </div>
      <p class="text-center desk_footer mt-5 leading-8 dark:text-gray-300">
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

<style scoped>
  .max_paragraph {
    max-width: 680px;
  }

  .Explore_our_leading {
    line-height: 50px;
  }

  .pfrm_red {
    text-shadow: 0px 0px 30px red;
  }

  .people_txt_glow {
    text-shadow: 0px 0px 30px rgb(2, 170, 236);
  }

  .discord_txt_glow {
    text-shadow: 0px 0px 30px purple;
  }

  .red_message_txt {
    text-shadow: 0px 0px 30px red;
  }
  /* .test_gradient_backgorund {
    border-radius: 30px;
    background: linear-gradient(to right, rgb(16, 17, 26), rgb(9, 12, 22));
    backdrop-filter: blur(40px);
    color: #fff;

    padding: 40px;
    box-shadow: 0 8px 72px 0 rgba(2, 2, 2, 0.37);
  } */
</style>
