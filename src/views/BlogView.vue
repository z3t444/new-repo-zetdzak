<script setup>
  import "../assets/css/responsive.css"
  import "../assets/css/graphpie.css"
  import GithubIco from "../assets/ico/githubIco.vue"
  import facebookIco from "../assets/ico/facebookIco.vue"
  import Insta from "../assets/ico/insta.vue"
  import pcIco from "../assets/ico/pcIco.vue"

  import ParallaxBlog from "../components/parallaxBlog.vue"
</script>

<template>
  <div class="dm_sans">
    <section>
      <div class="mt-10">
        <div class="xl:container m-auto px-6 text-gray-600 md:px-12 xl:px-16">
          <div class="dark:lg:bg-darker lg:p-16 rounded-[4rem] space-y-6 md:flex flex-row-reverse md:gap-6 justify-center md:space-y-0 lg:items-center">
            <div class="md:5/12 lg:w-1/2">
              <img src="../assets/img/staravatar.png" alt="image" loading="lazy" width="550px" height="" />
            </div>
            <div class="md:7/12 lg:w-1/2">
              <h2 class="text-5xl font-medium desk_avatarstar text-gray-900 md:text-4x leading-normal dark:text-white"><span class="text-sky-300 font-semibold" style="text-shadow: 0px 0px 30px rgb(0, 183, 255)">Nusantara Developer</span> is carried out by passionate developers</h2>
              <p class="my-8 text-gray-600 leading-8 text-sm dark:text-gray-300">Nobis minus voluptatibus pariatur dignissimos libero quaerat iure expedita at? Asperiores nemo possimus nesciunt dicta veniam aspernatur quam mollitia.</p>
              <div class="divide-y space-y-4 divide-gray-100 dark:divide-gray-800">
                <div class="mt-20 flex gap-4 md:items-center hover:scale-105 duration-100">
                  <div class="w-12 h-12 flex gap-4 rounded-full bg-indigo-100 dark:bg-indigo-900/20">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6 h-6 m-auto text-indigo-500 dark:text-indigo-400">
                      <path
                        fill-rule="evenodd"
                        d="M4.848 2.771A49.144 49.144 0 0112 2.25c2.43 0 4.817.178 7.152.52 1.978.292 3.348 2.024 3.348 3.97v6.02c0 1.946-1.37 3.678-3.348 3.97a48.901 48.901 0 01-3.476.383.39.39 0 00-.297.17l-2.755 4.133a.75.75 0 01-1.248 0l-2.755-4.133a.39.39 0 00-.297-.17 48.9 48.9 0 01-3.476-.384c-1.978-.29-3.348-2.024-3.348-3.97V6.741c0-1.946 1.37-3.68 3.348-3.97zM6.75 8.25a.75.75 0 01.75-.75h9a.75.75 0 010 1.5h-9a.75.75 0 01-.75-.75zm.75 2.25a.75.75 0 000 1.5H12a.75.75 0 000-1.5H7.5z"
                        clip-rule="evenodd" />
                    </svg>
                  </div>
                  <div class="w-5/6">
                    <h3 class="font-semibold text-lg text-gray-700 dark:text-indigo-300">Chat Anytime</h3>
                    <p class="text-gray-500 mt-3 text-sm dark:text-gray-400">Asperiores nemo possimus nesciunt quam mollitia.</p>
                  </div>
                </div>
                <div class="pt-4 flex gap-4 md:items-center hover:scale-105 duration-100">
                  <div class="w-12 h-12 flex gap-4 rounded-full bg-teal-100 dark:bg-teal-900/20">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6 h-6 m-auto text-teal-600 dark:text-teal-400">
                      <path fill-rule="evenodd" d="M11.54 22.351l.07.04.028.016a.76.76 0 00.723 0l.028-.015.071-.041a16.975 16.975 0 001.144-.742 19.58 19.58 0 002.683-2.282c1.944-1.99 3.963-4.98 3.963-8.827a8.25 8.25 0 00-16.5 0c0 3.846 2.02 6.837 3.963 8.827a19.58 19.58 0 002.682 2.282 16.975 16.975 0 001.145.742zM12 13.5a3 3 0 100-6 3 3 0 000 6z" clip-rule="evenodd" />
                    </svg>
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

    <section>
      <div class="ClassName ParallaxBlog mt-10 p-6 rounded-3xl" style="background-color: #1c1c2e">
        <ParallaxBlog />
      </div>
    </section>

    <div class="ClassName mt-14">
      <section class="p-6 rounded-3xl" style="background-color: #1c1c2e">
        <h3 class="dark:text-gray-200 text-3xl text-center lg:text-start xl:text-start font-medium">Our <span class="dark:text-orange-400">Skill</span> on Project ⚡</h3>
        <section class="ClassName mt-10">
          <div class="container p-6 mx-auto space-y-6 text-center lg:p-8 lg:space-y-8">
            <div class="flex flex-wrap justify-center lg:justify-around">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 32 32" aria-label="Angular" class="w-12 h-12 mx-10 my-6 fill-current md:mx-12 lg:m-0 dark:text-gray-400">
                <title>Angular</title>
                <path d="M13.24 16.859h5.51l-2.755-6.542zM15.995 0.010l-15.078 5.307 2.297 19.677 12.781 6.995 12.786-6.984 2.297-19.688-15.083-5.302zM25.406 24.406h-3.516l-1.896-4.667h-8l-1.896 4.667h-3.516l9.411-20.865z"></path>
              </svg>
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 32 32" aria-label="Gatsby" class="w-12 h-12 mx-10 my-6 fill-current md:mx-12 lg:m-0 dark:text-gray-400">
                <title>Gatsby</title>
                <path
                  d="M16 0.011c-8.901 0-15.989 7.088-15.989 15.989s7.088 15.995 15.989 15.995c8.901 0 15.989-7.093 15.989-15.995s-7.088-15.989-15.989-15.989zM3.484 16.14l12.38 12.376c-6.817 0-12.38-5.563-12.38-12.376zM18.781 28.24l-15.016-15.021c1.251-5.563 6.256-9.735 12.235-9.735 4.011 0.011 7.776 1.917 10.151 5.147l-1.807 1.531c-1.912-2.801-5.089-4.468-8.48-4.453-4.333-0.025-8.197 2.719-9.599 6.819l13.073 13.072c3.197-1.115 5.703-3.896 6.396-7.235h-5.423v-2.364h8.204c0 5.979-4.172 10.989-9.735 12.24z"></path>
              </svg>
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 32 32" aria-label="Plain HTML" class="w-12 h-12 mx-10 my-6 fill-current md:mx-12 lg:m-0 dark:text-gray-400">
                <title>Plain HTML</title>
                <path d="M2 0h28l-2.547 28.75-11.484 3.25-11.417-3.25zM11.375 13l-0.307-3.625 13.411 0.005 0.307-3.495-17.573-0.005 0.932 10.682h12.167l-0.432 4.568-3.88 1.068-3.938-1.078-0.255-2.813h-3.479l0.443 5.563 7.229 1.932 7.172-1.927 0.99-10.875z"></path>
              </svg>
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 32 32" aria-label="Next.js" class="w-12 h-12 mx-10 my-6 fill-current md:mx-12 lg:m-0 dark:text-gray-400">
                <title>Next.js</title>
                <path
                  d="M23.749 30.005c-0.119 0.063-0.109 0.083 0.005 0.025 0.037-0.015 0.068-0.036 0.095-0.061 0-0.021 0-0.021-0.1 0.036zM23.989 29.875c-0.057 0.047-0.057 0.047 0.011 0.016 0.036-0.021 0.068-0.041 0.068-0.047 0-0.027-0.016-0.021-0.079 0.031zM24.145 29.781c-0.057 0.047-0.057 0.047 0.011 0.016 0.037-0.021 0.068-0.043 0.068-0.048 0-0.025-0.016-0.020-0.079 0.032zM24.303 29.688c-0.057 0.047-0.057 0.047 0.009 0.015 0.037-0.020 0.068-0.041 0.068-0.047 0-0.025-0.016-0.020-0.077 0.032zM24.516 29.547c-0.109 0.073-0.147 0.12-0.047 0.068 0.067-0.041 0.181-0.131 0.161-0.131-0.043 0.016-0.079 0.043-0.115 0.063zM14.953 0.011c-0.073 0.005-0.292 0.025-0.484 0.041-4.548 0.412-8.803 2.86-11.5 6.631-1.491 2.067-2.459 4.468-2.824 6.989-0.129 0.88-0.145 1.14-0.145 2.333 0 1.192 0.016 1.448 0.145 2.328 0.871 6.011 5.147 11.057 10.943 12.927 1.043 0.333 2.136 0.563 3.381 0.704 0.484 0.052 2.577 0.052 3.061 0 2.152-0.24 3.969-0.771 5.767-1.688 0.276-0.14 0.328-0.177 0.291-0.208-0.88-1.161-1.744-2.323-2.609-3.495l-2.557-3.453-3.203-4.745c-1.068-1.588-2.14-3.172-3.229-4.744-0.011 0-0.025 2.109-0.031 4.681-0.011 4.505-0.011 4.688-0.068 4.792-0.057 0.125-0.151 0.229-0.276 0.287-0.099 0.047-0.188 0.057-0.661 0.057h-0.541l-0.141-0.088c-0.088-0.057-0.161-0.136-0.208-0.229l-0.068-0.141 0.005-6.271 0.011-6.271 0.099-0.125c0.063-0.077 0.141-0.14 0.229-0.187 0.131-0.063 0.183-0.073 0.724-0.073 0.635 0 0.74 0.025 0.907 0.208 1.296 1.932 2.588 3.869 3.859 5.812 2.079 3.152 4.917 7.453 6.312 9.563l2.537 3.839 0.125-0.083c1.219-0.813 2.328-1.781 3.285-2.885 2.016-2.308 3.324-5.147 3.767-8.177 0.129-0.88 0.145-1.141 0.145-2.333 0-1.193-0.016-1.448-0.145-2.328-0.871-6.011-5.147-11.057-10.943-12.928-1.084-0.343-2.199-0.577-3.328-0.697-0.303-0.031-2.371-0.068-2.631-0.041zM21.5 9.688c0.151 0.072 0.265 0.208 0.317 0.364 0.027 0.084 0.032 1.823 0.027 5.74l-0.011 5.624-0.989-1.52-0.995-1.521v-4.083c0-2.647 0.011-4.131 0.025-4.204 0.047-0.167 0.161-0.307 0.313-0.395 0.124-0.063 0.172-0.068 0.667-0.068 0.463 0 0.541 0.005 0.645 0.063z"></path>
              </svg>
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 32 32" aria-label="Nuxt.js" class="w-12 h-12 mx-10 my-6 fill-current md:mx-12 lg:m-0 dark:text-gray-400">
                <title>Nuxt.js</title>
                <path
                  d="M26.297 27.031l0.031-0.063c0.031-0.047 0.052-0.099 0.073-0.156v-0.005c0.099-0.26 0.12-0.536 0.073-0.813v0.010c-0.052-0.292-0.156-0.573-0.313-0.828l0.010 0.010-7.094-12.474-1.083-1.891-8.156 14.365c-0.141 0.25-0.229 0.521-0.276 0.802v0.016c-0.057 0.323-0.021 0.651 0.109 0.953l-0.005-0.010c0.016 0.047 0.042 0.089 0.068 0.135l-0.005-0.005c0.214 0.365 0.667 0.802 1.667 0.802h13.198c0.208 0 1.234-0.042 1.708-0.849zM17.995 14.609l6.479 11.396h-12.953zM31.661 25.188l-9.354-16.479c-0.099-0.177-0.635-1.052-1.578-1.052-0.422 0-1.026 0.182-1.521 1.047l-1.208 2.12 1.073 1.896 1.667-2.953 9.255 16.245h-3.521c0.047 0.271 0.021 0.547-0.073 0.807v-0.010c-0.021 0.057-0.042 0.115-0.073 0.167v-0.005l-0.031 0.063c-0.474 0.807-1.495 0.849-1.693 0.849h5.505c0.203 0 1.219-0.042 1.693-0.849 0.214-0.37 0.359-0.984-0.141-1.844zM9.74 27.078c-0.021-0.042-0.042-0.083-0.063-0.125v-0.005c-0.13-0.302-0.172-0.63-0.115-0.953v0.010h-7.563l11.24-19.776 3.687 6.484 1.073-1.891-3.219-5.667c-0.089-0.161-0.63-1.036-1.568-1.036-0.422 0-1.031 0.182-1.521 1.052l-11.385 20.016c-0.099 0.172-0.568 1.078-0.099 1.885 0.214 0.37 0.667 0.802 1.667 0.802h9.531c-0.99 0-1.453-0.427-1.667-0.802z"></path>
              </svg>
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 32 32" aria-label="React" class="w-12 h-12 mx-10 my-6 fill-current md:mx-12 lg:m-0 dark:text-gray-400">
                <title>React</title>
                <path
                  d="M16 13.146c-1.573 0-2.854 1.281-2.854 2.854s1.281 2.854 2.854 2.854c1.573 0 2.854-1.281 2.854-2.854s-1.281-2.854-2.854-2.854zM8.010 21.672l-0.63-0.156c-4.688-1.188-7.38-3.198-7.38-5.521s2.693-4.333 7.38-5.521l0.63-0.156 0.177 0.625c0.474 1.635 1.083 3.229 1.818 4.771l0.135 0.281-0.135 0.286c-0.734 1.536-1.344 3.13-1.818 4.771zM7.089 11.932c-3.563 1-5.75 2.536-5.75 4.063s2.188 3.057 5.75 4.063c0.438-1.391 0.964-2.745 1.578-4.063-0.615-1.318-1.141-2.672-1.578-4.063zM23.99 21.672l-0.177-0.625c-0.474-1.635-1.083-3.229-1.818-4.766l-0.135-0.286 0.135-0.286c0.734-1.536 1.344-3.13 1.818-4.771l0.177-0.62 0.63 0.156c4.688 1.188 7.38 3.198 7.38 5.521s-2.693 4.333-7.38 5.521zM23.333 15.995c0.641 1.385 1.172 2.745 1.578 4.063 3.568-1.005 5.75-2.536 5.75-4.063s-2.188-3.057-5.75-4.063c-0.438 1.385-0.964 2.745-1.578 4.063zM7.078 11.927l-0.177-0.625c-1.318-4.646-0.917-7.979 1.099-9.141 1.979-1.141 5.151 0.208 8.479 3.625l0.453 0.464-0.453 0.464c-1.182 1.229-2.26 2.552-3.229 3.958l-0.182 0.255-0.313 0.026c-1.703 0.135-3.391 0.406-5.047 0.813zM9.609 3.089c-0.359 0-0.677 0.073-0.943 0.229-1.323 0.766-1.557 3.422-0.646 7.005 1.422-0.318 2.859-0.542 4.313-0.672 0.833-1.188 1.75-2.323 2.734-3.391-2.078-2.026-4.047-3.172-5.458-3.172zM22.396 30.234c-0.005 0-0.005 0 0 0-1.901 0-4.344-1.427-6.875-4.031l-0.453-0.464 0.453-0.464c1.182-1.229 2.26-2.552 3.229-3.958l0.177-0.255 0.313-0.031c1.703-0.13 3.391-0.401 5.052-0.813l0.63-0.156 0.177 0.625c1.318 4.646 0.917 7.974-1.099 9.135-0.49 0.281-1.042 0.422-1.604 0.411zM16.932 25.729c2.078 2.026 4.047 3.172 5.458 3.172h0.005c0.354 0 0.672-0.078 0.938-0.229 1.323-0.766 1.563-3.422 0.646-7.005-1.422 0.318-2.865 0.542-4.313 0.667-0.833 1.193-1.75 2.323-2.734 3.396zM24.922 11.927l-0.63-0.161c-1.661-0.406-3.349-0.677-5.052-0.813l-0.313-0.026-0.177-0.255c-0.969-1.406-2.047-2.729-3.229-3.958l-0.453-0.464 0.453-0.464c3.328-3.417 6.5-4.766 8.479-3.625 2.016 1.161 2.417 4.495 1.099 9.141zM19.667 9.651c1.521 0.141 2.969 0.365 4.313 0.672 0.917-3.583 0.677-6.24-0.646-7.005-1.318-0.76-3.797 0.406-6.401 2.943 0.984 1.073 1.896 2.203 2.734 3.391zM9.609 30.234c-0.563 0.010-1.12-0.13-1.609-0.411-2.016-1.161-2.417-4.49-1.099-9.135l0.177-0.625 0.63 0.156c1.542 0.391 3.24 0.661 5.047 0.813l0.313 0.031 0.177 0.255c0.969 1.406 2.047 2.729 3.229 3.958l0.453 0.464-0.453 0.464c-2.526 2.604-4.969 4.031-6.865 4.031zM8.021 21.667c-0.917 3.583-0.677 6.24 0.646 7.005 1.318 0.75 3.792-0.406 6.401-2.943-0.984-1.073-1.901-2.203-2.734-3.396-1.453-0.125-2.891-0.349-4.313-0.667zM16 22.505c-1.099 0-2.224-0.047-3.354-0.141l-0.313-0.026-0.182-0.26c-0.635-0.917-1.24-1.859-1.797-2.828-0.563-0.969-1.078-1.958-1.557-2.969l-0.135-0.286 0.135-0.286c0.479-1.010 0.995-2 1.557-2.969 0.552-0.953 1.156-1.906 1.797-2.828l0.182-0.26 0.313-0.026c2.234-0.188 4.479-0.188 6.708 0l0.313 0.026 0.182 0.26c1.276 1.833 2.401 3.776 3.354 5.797l0.135 0.286-0.135 0.286c-0.953 2.021-2.073 3.964-3.354 5.797l-0.182 0.26-0.313 0.026c-1.125 0.094-2.255 0.141-3.354 0.141zM13.073 21.057c1.969 0.151 3.885 0.151 5.859 0 1.099-1.609 2.078-3.302 2.927-5.063-0.844-1.76-1.823-3.453-2.932-5.063-1.948-0.151-3.906-0.151-5.854 0-1.109 1.609-2.089 3.302-2.932 5.063 0.849 1.76 1.828 3.453 2.932 5.063z"></path>
              </svg>
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 32 32" aria-label="Svelte" class="w-12 h-12 mx-10 my-6 fill-current md:mx-12 lg:m-0 dark:text-gray-400">
                <title>Svelte</title>
                <path
                  d="M27.573 4.229c-2.927-4.25-8.656-5.479-13.068-2.802l-7.464 4.745c-2.042 1.281-3.443 3.365-3.854 5.734-0.365 1.969-0.047 4.005 0.891 5.776-0.641 0.964-1.073 2.052-1.266 3.198-0.427 2.406 0.13 4.885 1.547 6.88 2.932 4.24 8.646 5.474 13.068 2.828l7.469-4.75c2.031-1.281 3.427-3.365 3.839-5.734 0.359-1.964 0.042-3.995-0.896-5.755 1.984-3.115 1.88-7.12-0.266-10.12zM13.76 28.172c-2.401 0.625-4.938-0.318-6.349-2.359-0.865-1.198-1.182-2.677-0.932-4.146l0.146-0.708 0.135-0.438 0.401 0.266c0.88 0.667 1.865 1.146 2.917 1.469l0.271 0.094-0.031 0.266c-0.026 0.37 0.083 0.786 0.297 1.104 0.438 0.63 1.198 0.932 1.932 0.734 0.161-0.052 0.318-0.104 0.453-0.188l7.438-4.745c0.375-0.24 0.615-0.599 0.708-1.026 0.083-0.443-0.026-0.896-0.266-1.255-0.443-0.615-1.198-0.891-1.932-0.708-0.161 0.057-0.333 0.12-0.469 0.203l-2.813 1.786c-2.661 1.583-6.099 0.839-7.865-1.708-0.859-1.198-1.198-2.693-0.938-4.146 0.26-1.438 1.12-2.698 2.365-3.469l7.422-4.745c0.469-0.292 0.974-0.505 1.521-0.667 2.401-0.625 4.932 0.318 6.349 2.349 1 1.406 1.281 3.203 0.76 4.849l-0.135 0.443-0.385-0.266c-0.891-0.651-1.88-1.146-2.932-1.469l-0.266-0.078 0.026-0.266c0.026-0.391-0.083-0.802-0.297-1.12-0.438-0.63-1.198-0.896-1.932-0.708-0.161 0.052-0.318 0.104-0.453 0.188l-7.453 4.786c-0.375 0.25-0.615 0.599-0.693 1.036-0.078 0.427 0.026 0.896 0.266 1.24 0.427 0.63 1.203 0.896 1.922 0.708 0.172-0.052 0.333-0.104 0.464-0.188l2.844-1.813c0.464-0.307 0.984-0.531 1.516-0.677 2.417-0.63 4.938 0.318 6.349 2.359 0.865 1.198 1.198 2.677 0.958 4.13-0.25 1.438-1.099 2.698-2.333 3.469l-7.438 4.734c-0.484 0.292-1.005 0.521-1.547 0.677z"></path>
              </svg>
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 32 32" aria-label="Vue.js" class="w-12 h-12 mx-10 my-6 fill-current md:mx-12 lg:m-0 dark:text-gray-400">
                <title>Vue.js</title>
                <path d="M24.306 4.019h-4.806l-3.5 5.537-3-5.537h-11l14 23.981 14-23.981zM5.481 6.019h3.363l7.156 12.387 7.15-12.387h3.363l-10.512 18.012z"></path>
              </svg>
            </div>
          </div>
        </section>
      </section>
    </div>

    <!-- Hero -->

    <!-- End Hero -->
    <section class="ClassName mt-40">
      <div class="container px-6 py-10 mx-auto">
        <h1 class="text-2xl font-semibold text-gray-800 capitalize lg:text-3xl dark:text-white">explore our awesome <span class="dark:text-blue-400">Components 🔍</span></h1>

        <p class="mt-4 text-gray-500 xl:mt-8 leading-8 dark:text-gray-300 xl:w-2/6">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Nostrum quam voluptatibus</p>

        <div class="grid grid-cols-1 gap-8 mt-8 xl:mt-20 xl:gap-17 md:grid-cols-2 xl:grid-cols-3">
          <div class="space-y-3 p-10 rounded-3xl" style="background-color: #1c1c2e">
            <span class="inline-block p-3 text-blue-500 bg-blue-100 rounded-full dark:text-white dark:bg-blue-500">
              <svg xmlns="http://www.w3.org/2000/svg" class="w-6 h-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5H7a2 2 0 00-2 2v12a2 2 0 002 2h10a2 2 0 002-2V7a2 2 0 00-2-2h-2M9 5a2 2 0 002 2h2a2 2 0 002-2M9 5a2 2 0 012-2h2a2 2 0 012 2m-3 7h3m-3 4h3m-6-4h.01M9 16h.01" />
              </svg>
            </span>
            <h1 class="text-xl font-semibold text-gray-700 capitalize dark:text-white">Copy & paste components</h1>
            <p class="text-gray-500 text-sm leading-7 dark:text-gray-300">Lorem ipsum dolor sit amet consectetur adipisicing elit. Provident ab nulla quod dignissimos vel non corrupti doloribus voluptatum eveniet</p>
          </div>

          <div class="space-y-3 p-10 rounded-3xl" style="background-color: #1c1c2e">
            <span class="inline-block p-3 text-blue-500 bg-blue-100 rounded-full dark:text-white dark:bg-blue-500">
              <svg xmlns="http://www.w3.org/2000/svg" class="w-6 h-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6V4m0 2a2 2 0 100 4m0-4a2 2 0 110 4m-6 8a2 2 0 100-4m0 4a2 2 0 110-4m0 4v2m0-6V4m6 6v10m6-2a2 2 0 100-4m0 4a2 2 0 110-4m0 4v2m0-6V4" />
              </svg>
            </span>
            <h1 class="text-xl font-semibold text-gray-700 capitalize dark:text-white">Zero Configuration</h1>
            <p class="text-gray-500 text-sm leading-7 dark:text-gray-300">Lorem ipsum dolor sit amet consectetur adipisicing elit. Provident ab nulla quod dignissimos vel non corrupti doloribus voluptatum eveniet</p>
          </div>

          <div class="space-y-3 p-10 rounded-3xl" style="background-color: #1c1c2e">
            <span class="inline-block p-3 text-blue-500 bg-blue-100 rounded-full dark:text-white dark:bg-blue-500">
              <svg xmlns="http://www.w3.org/2000/svg" class="w-6 h-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 19v-6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2a2 2 0 002-2zm0 0V9a2 2 0 012-2h2a2 2 0 012 2v10m-6 0a2 2 0 002 2h2a2 2 0 002-2m0 0V5a2 2 0 012-2h2a2 2 0 012 2v14a2 2 0 01-2 2h-2a2 2 0 01-2-2z" />
              </svg>
            </span>
            <h1 class="text-xl font-semibold text-gray-700 capitalize dark:text-white">New Components Every month</h1>
            <p class="text-gray-500 text-sm leading-7 dark:text-gray-300">Lorem ipsum dolor sit amet consectetur adipisicing elit. Provident ab nulla quod dignissimos vel non corrupti doloribus voluptatum eveniet</p>
          </div>

          <div class="space-y-3 p-10 rounded-3xl" style="background-color: #1c1c2e">
            <span class="inline-block p-3 text-blue-500 bg-blue-100 rounded-full dark:text-white dark:bg-blue-500">
              <svg xmlns="http://www.w3.org/2000/svg" class="w-6 h-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 18.657A8 8 0 016.343 7.343S7 9 9 10c0-2 .5-5 2.986-7C14 5 16.09 5.777 17.656 7.343A7.975 7.975 0 0120 13a7.975 7.975 0 01-2.343 5.657z" />
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9.879 16.121A3 3 0 1012.015 11L11 14H9c0 .768.293 1.536.879 2.121z" />
              </svg>
            </span>
            <h1 class="text-xl font-semibold text-gray-700 capitalize dark:text-white">elegant Dark Mode</h1>
            <p class="text-gray-500 text-sm leading-7 dark:text-gray-300">Lorem ipsum dolor sit amet consectetur adipisicing elit. Provident ab nulla quod dignissimos vel non corrupti doloribus voluptatum eveniet</p>
          </div>

          <div class="space-y-3 p-10 rounded-3xl" style="background-color: #1c1c2e">
            <span class="inline-block p-3 text-blue-500 bg-blue-100 rounded-full dark:text-white dark:bg-blue-500">
              <svg xmlns="http://www.w3.org/2000/svg" class="w-6 h-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M11 4a2 2 0 114 0v1a1 1 0 001 1h3a1 1 0 011 1v3a1 1 0 01-1 1h-1a2 2 0 100 4h1a1 1 0 011 1v3a1 1 0 01-1 1h-3a1 1 0 01-1-1v-1a2 2 0 10-4 0v1a1 1 0 01-1 1H7a1 1 0 01-1-1v-3a1 1 0 00-1-1H4a2 2 0 110-4h1a1 1 0 001-1V7a1 1 0 011-1h3a1 1 0 001-1V4z" />
              </svg>
            </span>
            <h1 class="text-xl font-semibold text-gray-700 capitalize dark:text-white">Easy to customiztions</h1>
            <p class="text-gray-500 text-sm leading-7 dark:text-gray-300">Lorem ipsum dolor sit amet consectetur adipisicing elit. Provident ab nulla quod dignissimos vel non corrupti doloribus voluptatum eveniet</p>
          </div>

          <div class="space-y-3 p-10 rounded-3xl" style="background-color: #1c1c2e">
            <span class="inline-block p-3 text-blue-500 bg-blue-100 rounded-full dark:text-white dark:bg-blue-500">
              <svg xmlns="http://www.w3.org/2000/svg" class="w-6 h-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 3v4M3 5h4M6 17v4m-2-2h4m5-16l2.286 6.857L21 12l-5.714 2.143L13 21l-2.286-6.857L5 12l5.714-2.143L13 3z" />
              </svg>
            </span>
            <h1 class="text-xl font-semibold text-gray-700 capitalize dark:text-white">Simple & clean designs</h1>
            <p class="text-gray-500 text-sm leading-7 dark:text-gray-300">Lorem ipsum dolor sit amet consectetur adipisicing elit. Provident ab nulla quod dignissimos vel non corrupti doloribus voluptatum eveniet</p>
          </div>
        </div>
      </div>
    </section>

    <section class="mt-40 main_txt_pricing">
      <h3 class="text-3xl dark:text-white font-medium">Lorem <span class="dark:text-sky-400 blue_shadow">ipsum</span> dolor sit amet <span class="dark:text-blue-400 blue_normal">consectetur</span>.</h3>
      <p class="xl:w-1/3 mt-6 dark:text-gray-300 leading-8">Lorem ipsum dolor sit amet consectetur adipisicing elit. Inventore nostrum, possimus unde consequuntur obcaecati neque. Distinctio nesciunt sunt explicabo odit.</p>
    </section>
    <section>
      <div class="flex items-center gap-20 justify-center mt-20 p-20 rounded-3xl" style="background-color: #1c1c2e">
        <div class="pie animate" style="--p: 50">50%</div>
        <div class="pie animate" style="--p: 25; --c: darkblue; --b: 10px">25%</div>
        <div class="pie animate no-round" style="--p: 60; --c: purple; --b: 15px">60%</div>
        <div class="pie animate no-round" style="--p: 40; --c: orange">40%</div>
        <div class="pie animate" style="--p: 90; --c: lightgreen">90%</div>
      </div>
    </section>

    <section>
      <div class="relative overflow-hidden mt-10 rounded-3xl">
        <div class="relative z-10">
          <div class="max-w-[85rem] mx-auto px-4 sm:px-6 lg:px-8 py-10 lg:py-16">
            <div class="max-w-3xl text-center mx-auto">
              <p class="inline-block text-sm font-medium dark:text-gray-200">Solution Problem Solving</p>

              <!-- Title -->
              <div class="ClassName mt-7">
                <h3 class="text-6xl dark:text-gray-200 font-medium">The Intuitive Web Solutions</h3>
              </div>
              <!-- End Title -->

              <div class="mt-8 max-w-3xl">
                <p class="text-sm leading-8 xl:w-3/4 mx-auto text-gray-600 dark:text-gray-300">Preline UI is an open-source set of prebuilt UI components, ready-to-use examples and Figma design system based on the utility-first Tailwind CSS framework.</p>
              </div>

              <!-- Buttons -->
              <div class="mt-12 gap-3 flex justify-center">
                <a class="py-3 px-4 inline-flex items-center gap-x-2 text-sm font-semibold rounded-2xl border border-transparent bg-blue-500 text-white hover:bg-blue-500 hover:scale-95 duration-100 disabled:opacity-50 disabled:pointer-events-none dark:focus:outline-none dark:focus:ring-1 dark:focus:ring-gray-600" href="#">
                  Get started
                  <svg class="flex-shrink-0 w-4 h-4" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                    <path d="m9 18 6-6-6-6" />
                  </svg>
                </a>
              </div>
              <!-- End Buttons -->
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="ClassName mt-20">
      <div class="container px-6 py-10 mx-auto">
        <h1 class="text-2xl font-semibold text-gray-800 capitalize lg:text-3xl dark:text-white">
          explore our <br />
          awesome <span class="underline decoration-blue-500">Components</span>
        </h1>

        <p class="mt-4 text-gray-500 xl:mt-6 dark:text-gray-300">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Nostrum quam voluptatibus</p>
        <div class="grid grid-cols-1 gap-8 mt-8 xl:mt-20 xl:gap-8 md:grid-cols-2 xl:grid-cols-3">
          <div class="p-8 space-y-6 border border-gray-400 dark:border-gray-800 hover:dark:border-sky-400 rounded-3xl hover:scale-105 duration-100" style="background-color: #1c1c2e">
            <span class="inline-block text-blue-500 dark:text-blue-400">
              <svg xmlns="http://www.w3.org/2000/svg" class="w-8 h-8" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 18.657A8 8 0 016.343 7.343S7 9 9 10c0-2 .5-5 2.986-7C14 5 16.09 5.777 17.656 7.343A7.975 7.975 0 0120 13a7.975 7.975 0 01-2.343 5.657z" />
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9.879 16.121A3 3 0 1012.015 11L11 14H9c0 .768.293 1.536.879 2.121z" />
              </svg>
            </span>
            <h1 class="text-2xl font-semibold text-gray-700 capitalize dark:text-white">elegant Dark Mode</h1>
            <p class="text-gray-500 text-sm leading-7 dark:text-gray-300">Lorem ipsum dolor sit amet consectetur adipisicing elit. Provident ab nulla quod dignissimos vel non corrupti doloribus voluptatum eveniet</p>
          </div>

          <div class="p-8 space-y-6 border border-blue-400 dark:border-gray-800 hover:dark:border-sky-400 rounded-3xl hover:scale-105 duration-100" style="background-color: #1c1c2e">
            <span class="inline-block text-blue-500 dark:text-blue-400">
              <svg xmlns="http://www.w3.org/2000/svg" class="w-8 h-8" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M11 4a2 2 0 114 0v1a1 1 0 001 1h3a1 1 0 011 1v3a1 1 0 01-1 1h-1a2 2 0 100 4h1a1 1 0 011 1v3a1 1 0 01-1 1h-3a1 1 0 01-1-1v-1a2 2 0 10-4 0v1a1 1 0 01-1 1H7a1 1 0 01-1-1v-3a1 1 0 00-1-1H4a2 2 0 110-4h1a1 1 0 001-1V7a1 1 0 011-1h3a1 1 0 001-1V4z" />
              </svg>
            </span>
            <h1 class="text-2xl font-semibold text-gray-700 capitalize dark:text-white">Easy to customiztions</h1>
            <p class="text-gray-500 text-sm leading-7 dark:text-gray-300">Lorem ipsum dolor sit amet consectetur adipisicing elit. Provident ab nulla quod dignissimos vel non corrupti doloribus voluptatum eveniet</p>
          </div>

          <div class="p-8 space-y-6 border border-blue-400 dark:border-gray-800 hover:dark:border-sky-400 rounded-3xl hover:scale-105 duration-100" style="background-color: #1c1c2e">
            <span class="inline-block text-blue-500 dark:text-blue-400">
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

    <div class="viewFooter mt-40 dm_sans">
      <div class="ClassName flex space-x-3 justify-center items-center">
        <pcIco />
        <h3 class="text-4xl dark:text-gray-200 font-semibold">Nusantara Developer</h3>
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
  @import url("https://fonts.googleapis.com/css2?family=DM+Sans:ital,opsz,wght@0,9..40,300;0,9..40,400;0,9..set40,500;0,9..40,600;0,9..40,700;0,9..40,800;0,9..40,900;0,9..40,1000;1,9..40,300;1,9..40,400;1,9..40,500;1,9..40,600;1,9..40,700;1,9..40,800;1,9..40,900;1,9..40,1000&display=swap");
  @import url("https://fonts.googleapis.com/css2?family=DM+Sans:ital,opsz,wght@0,9..40,300;0,9..40,400;0,9..40,500;0,9..40,600;0,9..40,700;0,9..40,800;0,9..40,900;0,9..40,1000;1,9..40,300;1,9..40,400;1,9..40,500;1,9..40,600;1,9..40,700;1,9..40,800;1,9..40,900;1,9..40,1000&display=swap");

  .dm_sans {
    font-family: "DM Sans", sans-serif;
  }

  .blue_shadow {
    text-shadow: 0px 0px 30px rgb(0, 191, 255);
  }

  .blue_normal {
    text-shadow: 0px 0px 30px rgb(0, 140, 255);
  }
</style>
