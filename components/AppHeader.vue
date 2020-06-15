<template>
  <div>
    <nav class="bg-white shadow">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="flex h-32">
          <div class="flex">
            <nuxt-link to="/" class="text-indigo-600 font-semibold w-1/6">
              <img class src="../assets/bearcotlogo.jpeg">
            </nuxt-link>

            <div class="hidden sm:ml-6 sm:flex">
              <nuxt-link
                to="/"
                exact-active-class="nav-link text-gray-700"
                class="inline-flex items-center px-1 pt-1 border-b-2 border-transparent text-sm font-medium leading-5 text-gray-500 hover:text-gray-700 hover:border-gray-300 focus:outline-none transition duration-150 ease-in-out"
              >Home</nuxt-link>
              <nuxt-link
                to="about"
                exact-active-class="nav-link text-gray-700"
                class="ml-8 inline-flex items-center px-1 pt-1 border-b-2 border-transparent text-sm font-medium leading-5 text-gray-500 hover:text-gray-700 hover:border-gray-300 focus:outline-none transition duration-150 ease-in-out"
              >About</nuxt-link>
              <nuxt-link
                to="contact"
                exact-active-class="nav-link text-gray-700"
                class="ml-8 inline-flex items-center px-1 pt-1 border-b-2 border-transparent text-sm font-medium leading-5 text-gray-500 hover:text-gray-700 hover:border-gray-300 focus:outline-none transition duration-150 ease-in-out"
              >Contact</nuxt-link>
              <nuxt-link
                to="product"
                exact-active-class="nav-link text-gray-700"
                class="ml-8 inline-flex items-center px-1 pt-1 border-b-2 border-transparent text-sm font-medium leading-5 text-gray-500 hover:text-gray-700 hover:border-gray-300 focus:outline-none transition duration-150 ease-in-out"
              >Product</nuxt-link>
            </div>
          </div>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: "AppHeader"
};
</script>

<style scoped>
.nav-link {
  border-color: #d76310;
}
</style>