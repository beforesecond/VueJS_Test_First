<template>
  <div class="max-w-5xl px-6 mx-auto text-center mt-10">
    <h2 class="text-2xl font-semibold text-gray-800">My Favorite Frontend Framwork</h2>

    <div class="flex items-center justify-center mt-10">
      <div class="grid grid-cols-1 gap-6 sm:grid-cols-2 lg:grid-cols-3">
        <div class="max-w-xs w-full">
          <div
            class="flex items-center justify-center h-56 bg-white border-b-8 border-teal-400 rounded-md overflow-hidden"
          >
            <img
              class="object-cover h-56"
              src="https://i.postimg.cc/kGxtmgDn/20167174151551942641-512.png"
              alt
            />
          </div>

          <a
            href="https://reactjs.org"
            class="block bg-gray-700 mt-5 rounded-md overflow-hidden transition duration-500 ease-in-out transform hover:-translate-y-1 hover:scale-110"
          >
            <div class="py-2 px-3 text-center text-sm">
              <p class="text-gray-300">ReactJS</p>

              <span class="block text-gray-500 mt-2">reactjs.org</span>
            </div>
          </a>
        </div>

        <div class="max-w-xs w-full">
          <div
            class="flex items-center justify-center h-56 bg-white border-b-8 border-teal-400 rounded-md overflow-hidden"
          >
            <img class="object-cover h-56" src="https://vuejs.org/images/logo.png" alt />
          </div>

          <a
            href="https://vuejs.org"
            class="block bg-gray-700 mt-5 rounded-md overflow-hidden transition duration-500 ease-in-out transform hover:-translate-y-1 hover:scale-110"
          >
            <div class="py-2 px-3 text-center text-sm">
              <p class="text-gray-300">VueJS</p>

              <span class="block text-gray-500 mt-2">vuejs.org</span>
            </div>
          </a>
        </div>

        <div class="max-w-xs w-full">
          <div
            class="flex items-center justify-center h-56 bg-white border-b-8 border-teal-400 rounded-md overflow-hidden"
          >
            <img
              class="object-cover h-56"
              src="https://angular.io/assets/images/logos/angular/angular.svg"
              alt
            />
          </div>

          <a
            href="https://angular.io"
            class="block bg-gray-700 mt-5 rounded-md overflow-hidden transition duration-500 ease-in-out transform hover:-translate-y-1 hover:scale-110"
          >
            <div class="py-2 px-3 text-center text-sm">
              <p class="text-gray-300">Angular</p>

              <span class="block text-gray-500 mt-2">angular.io</span>
            </div>
          </a>
        </div>
      </div>
    </div>

    <div class="flex items-center justify-center mt-12">
      <a class="flex items-center text-white hover:underline hover:text-gray-200" href="#">
        <svg class="h-5 w-5 ml-1" fill="none" viewBox="0 0 24 24" stroke="currentColor">
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M17 8l4 4m0 0l-4 4m4-4H3"
          />
        </svg>
      </a>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Framework'
}
</script>