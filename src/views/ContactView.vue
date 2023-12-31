<template>
  <div class="mt-20 w-full">
    <form action="https://api.web3forms.com/submit" method="POST" class="grid gap-4 max-w-5xl mx-auto p-4 rounded-lg">
      <input type="hidden" name="access_key" value="3a928331-13f9-4e84-86cf-adb4fb41d57e" />
      <div class="flex flex-col gap-4">
        <input type="text" name="name" required placeholder="Username" class="w-full px-3 py-2 rounded-xl shadow-lg focus:outline-none bg-transparent focus:border-blue-500" style="background-color: #1c1c2e" />
        <input type="text" name="name" required placeholder="Password" class="w-full px-3 py-2 rounded-xl shadow-lg focus:outline-none bg-transparent focus:border-blue-500" style="background-color: #1c1c2e" />
        <input type="email" name="email" required placeholder="Your Email" class="w-full px-3 py-2 rounded-xl shadow-lg focus:outline-none bg-transparent focus:border-blue-500" style="background-color: #1c1c2e" />
        <textarea name="message" required placeholder="Your Message /default : I need login in Form" class="w-full px-3 py-2 h-40 rounded-xl shadow-lg focus:outline-none bg-transparent focus:border-blue-500" style="background-color: #1c1c2e"></textarea>
        <button type="submit" class="w-full max-w-xs mx-auto py-2 px-4 text-sm text-white font-semibold rounded-xl hover:bg-blue-600 focus:outline-none duration-100 focus:bg-blue-600" style="background-color: #1c1c2e">Submit Form</button>
      </div>
    </form>
  </div>
</template>
