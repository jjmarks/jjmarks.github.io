<template>
  <nav
    class="w-full flex flex-wrap items-center justify-between px-2 pt-3 mb-1 md:mb-4 navbar-expand-lg"
  >
    <div class="container mx-auto">
      <div
        class="flex flex-wrap items-center md:justify-between justify-center"
      >
        <div class="w-full md:w-1/4 px-4 mt-2">
          <ul class="flex flex-wrap list-none md:justify-start justify-center">
            <li>
              <NuxtLink
                to="/"
                class="text-gray-200 hover:text-gray-400 text-2xl font-semibold py-1"
                >JMarks.net</NuxtLink
              >
            </li>
          </ul>
        </div>
        <div class="w-full md:w-4/12 px-4 mt-2">
          <ul class="flex flex-wrap list-none md:justify-end justify-center">
            <li>
              <a
                href="https://www.linkedin.com/in/josephjmarks/"
                class="text-gray-200 hover:text-gray-400 text font-semibold py-1 px-3"
                target="_blank"
                >LinkedIn</a
              >
            </li>
            <li>
              <a
                href="https://www.twitter.com/MrJMarks"
                class="text-gray-200 hover:text-gray-400 text font-semibold py-1 px-3"
                target="_blank"
                >Twitter</a
              >
            </li>
            <li>
              <a
                href="https://goodreads.com/jjmarks"
                class="text-gray-200 hover:text-gray-400 text font-semibold py-1 px-3"
                target="_blank"
                >Goodreads</a
              >
            </li>
          </ul>
        </div>
        <div class="w-full md:w-1/3 mt-2">
          <ul class="flex flex-wrap list-none md:justify-end justify-center">
            <li>
              <NuxtLink
                to="/"
                class="text-gray-200 hover:text-gray-400 text font-semibold py-1 px-3"
                >Home</NuxtLink
              >
            </li>
            <li>
              <NuxtLink
                to="/projects"
                class="text-gray-200 hover:text-gray-400 text font-semibold py-1 px-3"
                >Projects</NuxtLink
              >
            </li>
            <li>
              <NuxtLink
                to="/resume"
                class="text-gray-200 hover:text-gray-400 text font-semibold py-1 px-3"
                >CV</NuxtLink
              >
            </li>
          </ul>
        </div>
      </div>
    </div>
  </nav>
</template>

<script>
export default {}
</script>
