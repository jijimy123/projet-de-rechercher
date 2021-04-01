<template>
  <div
    class="px-4 py-16 mx-auto sm:max-w-xl md:max-w-full lg:max-w-screen-xl md:px-24 lg:px-8 lg:py-20"
  >
    <div class="mb-10 border-t border-b divide-y">
      <div class="grid py-8 sm:grid-cols-4">
        <div class="mb-4 sm:mb-0">
          <div class="space-y-1 text-xs font-semibold tracking-wide uppercase">
            <a
              href="/"
              class="transition-colors duration-200 text-deep-purple-accent-400 hover:text-deep-purple-800"
              aria-label="Category"
              >Anniversaire</a
            >
            <p class="text-gray-600">5 Jan 2020</p>
          </div>
        </div>
        <div class="sm:col-span-3 lg:col-span-2">
          <div class="mb-3"></div>
          <p class="text-gray-700">
            C'est la fête de quelqu'un. Il faut que tu prépare quelque chose
            pour lui.
          </p>
        </div>
      </div>
    </div>
    <!-- Boutons -->
    <div class="text-center text-4xl">
      <button
        class="inline-flex items-center justify-center w-full h-12 px-6 font-medium tracking-wide text-white transition duration-200 rounded shadow-md md:w-auto bg-deep-purple-accent-400 hover:bg-deep-purple-accent-700 focus:shadow-outline focus:outline-none"
      >
        +
      </button>
    </div>
  </div>
</template>

<script>
export default {
  name: "Tableau",
};
</script>