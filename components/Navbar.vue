<template>

  <nav class="bg-white dark:bg-gray-900 fixed w-full z-50 top-0 left-0 border-b border-gray-200 dark:border-gray-600">
    <div class="max-w-screen-xl flex flex-wrap items-center justify-between mx-auto p-4">
      <a href="#" class="flex items-center">
        <img
          src="https://media.discordapp.net/attachments/1199749587422941275/1218494409952333895/autozeit_-_Copy.png?ex=6607de59&is=65f56959&hm=111fc8f979f8615f287af2bb6fa808ae3890d961238e75bf0176019f0e28da32&=&format=webp&quality=lossless"
          class="h-8 mr-3" alt="Logo">
      </a>
      <div class="flex md:order-2">
        <!-- Cumpara button -->
        <button type="button"
          class="text-white bg-slate-700 hover:bg-slate-800 focus:ring-4 focus:outline-none focus:ring-gray-200 font-medium rounded-3xl transition duration-300 text-sm px-4 py-2 text-center mr-3 md:mr-0 dark:bg-red-500 dark:hover:bg-red-600 dark:focus:ring-gray-200"><a
            href="#produse">Login</a></button>
        <button id="toggleMenu" type="button"
          class="inline-flex items-center p-2 w-10 h-10 justify-center text-sm text-gray-500 rounded-lg md:hidden hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-gray-200 dark:text-gray-400 dark:hover:bg-gray-700 dark:focus:ring-gray-600"
          aria-controls="navbar-sticky" aria-expanded="false">
          <span class="sr-only">Deschide meniul</span>
          <svg class="w-5 h-5" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 17 14">
            <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
              d="M1 1h15M1 7h15M1 13h15" />
          </svg>
        </button>
      </div>
      <div class="items-center justify-between hidden w-full md:flex md:w-auto md:order-1" id="navbar-sticky">
        <ul
          class="flex flex-col p-4 md:p-0 mt-4 font-medium border border-gray-100 rounded-lg bg-gray-50 md:flex-row md:space-x-8 md:mt-0 md:border-0 md:bg-white dark:bg-gray-800 md:dark:bg-gray-900 dark:border-gray-700">
          <li>
            <NuxtLink to="/" class="block py-2 pl-3 pr-4 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:hover:text-amber-500 md:p-0 md:dark:hover:text-amber-500 dark:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700 transition duration-300">Acasă</NuxtLink>
          </li>
          <li>
            <NuxtLink to="/istorie" class="block py-2 pl-3 pr-4 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:hover:text-amber-500 md:p-0 md:dark:hover:text-amber-500 dark:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700 transition duration-300">Istorie</NuxtLink>
          </li>
          <li>
            <NuxtLink to="/colectie" class="block py-2 pl-3 pr-4 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:hover:text-amber-500 md:p-0 md:dark:hover:text-amber-500 dark:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700 transition duration-300">Colectie</NuxtLink>
          </li>
          <li>
            <NuxtLink to="/service" class="block py-2 pl-3 pr-4 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:hover:text-amber-500 md:p-0 md:dark:hover:text-amber-500 dark:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700 transition duration-300">Service</NuxtLink>
          </li>
        </ul>
      </div>
    </div>
  </nav>

</template>

<script>
export default {
  mounted() {
    document.getElementById('toggleMenu').addEventListener('click', function () {
      document.getElementById('navbar-sticky').classList.toggle('hidden');
    });
  }
}
</script>
