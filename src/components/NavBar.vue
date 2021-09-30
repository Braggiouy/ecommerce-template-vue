<template>
  <header class="text-white bg-purple-900 body-font w-full">
    <div
      class="
        flex flex-row
        items-center
        py-2
        justify-end
        sm:space-bet sm:space-x-2
        space-x-4
      "
    >
      <div class="flex items-center text-base justify-center">
        <p>12</p>
        <svg
          xmlns="http://www.w3.org/2000/svg"
          class="h-5 w-5 hover:bg-purple-600 rounded-md"
          fill="none"
          viewBox="0 0 24 24"
          stroke="currentColor"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M16 11V7a4 4 0 00-8 0v4M5 9h14l1 12H4L5 9z"
          />
        </svg>
      </div>
      <div>
        <a class="hover:text-white cursor-pointer text-s underline"
          >My account</a
        >
      </div>
      <div class="">
        <input
          class="
            inline-flex
            items-center
            bg-gray-800
            border-0
            focus:outline-none focus:ring-2 focus:
            ring-purple-600
            focus:
            border-transparent
            hover:bg-gray-700
            rounded-full
            text-base text-white
            mr-2
          "
        />
      </div>
    </div>

    <!-- Second Nav Bar -->
    <div class="bg-red-500 flex flex-row md:justify-between p-5">
      <div class="p-1">
        <p
          class="
            cursor-pointer
            whitespace-nowrap
            font-semibold
            md:text-xl
            lg:text-2xl
          "
        >
          Canary Game
        </p>
      </div>

      <div class="sm:hidden p-1 space-x-1 mr-1">
        <a class="hover:text-purple-600 cursor-pointer">Home</a>
        <a class="hover:text-purple-600 cursor-pointer">Event</a>
        <a class="hover:text-purple-600 cursor-pointer">Accesories</a>
        <a class="hover:text-purple-600 cursor-pointer">Apparel</a>
        <a class="hover:text-purple-600 cursor-pointer">Featured Items</a>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "NavBar",
  props: {},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped></style>
