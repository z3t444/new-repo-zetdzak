<script setup>
  import GithubIco from "../assets/ico/githubIco.vue"
  import facebookIco from "../assets/ico/facebookIco.vue"
  import Insta from "../assets/ico/insta.vue"
  import pcIco from "../assets/ico/pcIco.vue"
</script>

<template>
  <div class="ClassName text-center mt-32 p-5 dm_sans">
    <h3 class="text-5xl font-medium dark:text-gray-200">You can leave a message below 💬</h3>
    <p class="xl:w-1/4 mx-auto mt-5 text-gray-400">Tell me whatever it is. give us the best message so that we are more enthusiastic to work.</p>
  </div>
  <div class="mt-5 w-full">
    <form action="https://api.web3forms.com/submit" method="POST" class="grid gap-4 max-w-5xl mx-auto p-4 rounded-lg">
      <input type="hidden" name="access_key" value="3a928331-13f9-4e84-86cf-adb4fb41d57e" />
      <div class="flex flex-col gap-4">
        <input type="text" name="name" required placeholder="Username" class="w-full px-3 py-2 rounded-xl shadow-lg focus:outline-none bg-transparent focus:border-blue-500" style="background-color: #1c1c2e" />
        <input type="password" name="password" required placeholder="Password" class="w-full px-3 py-2 rounded-xl shadow-lg focus:outline-none bg-transparent focus:border-blue-500" style="background-color: #1c1c2e" />
        <input type="email" name="email" required placeholder="Your Email" class="w-full px-3 py-2 rounded-xl shadow-lg focus:outline-none bg-transparent focus:border-blue-500" style="background-color: #1c1c2e" />
        <textarea name="message" required placeholder="Your Message /default : I need login in Form" class="w-full px-3 py-2 h-40 rounded-xl shadow-lg focus:outline-none bg-transparent focus:border-blue-500" style="background-color: #1c1c2e"></textarea>
        <button type="submit" class="w-full max-w-xs mx-auto py-2 px-4 text-sm text-white font-semibold mt-5 rounded-xl hover:bg-blue-600 focus:outline-none duration-100 focus:bg-blue-600" style="background-color: #1c1c2e">Submit Form</button>
      </div>
    </form>
  </div>

  <div class="viewFooter mt-40 dm_sans">
    <div class="ClassName flex space-x-3 justify-center items-center">
      <pcIco />
      <h3 class="text-4xl dark:text-gray-200 font-semibold">ZetDzak</h3>
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
</template>
