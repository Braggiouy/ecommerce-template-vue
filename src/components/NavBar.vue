<template>
  <header class="text-white bg-blue-800 body-font w-full">
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
      <div class="flex items-center text-base justify-center sm:ml-2">
        <p>3</p>
        <svg
          xmlns="http://www.w3.org/2000/svg"
          class="h-5 w-5 cursor-pointer hover:text-red-300 rounded-md"
          fill="none"
          viewBox="0 0 24 24"
          stroke="currentColor"
          @click="openShoppingList"
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
        <a
          class="
            hover:text-red-300
            cursor-pointer
            text-s
            underline
            whitespace-nowrap
          "
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
            p-1
          "
        />
      </div>
    </div>

    <!-- Second Nav Bar -->
    <div class="bg-green-500 flex flex-row justify-between p-5">
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
          Canary Store
        </p>
      </div>

      <div class="sm:hidden p-1 space-x-3 mr-1">
        <a class="hover:text-purple-800 cursor-pointer">Home</a>
        <a class="hover:text-purple-800 cursor-pointer">Event</a>
        <a class="hover:text-purple-800 cursor-pointer">Accesories</a>
        <a class="hover:text-purple-800 cursor-pointer">Apparel</a>
        <a class="hover:text-purple-800 cursor-pointer">Featured Items</a>
      </div>
      <!-- dropdown menu -->
      <select
        class="
          block
          w-52
          text-gray-700
          py-2
          px-3
          border border-gray-300
          bg-white
          rounded-md
          shadow-sm
          focus:outline-none focus:ring-primary-500 focus:border-primary-500
          mx-1
          md:hidden
          lg:hidden
          xl:hidden
          2xl:hidden
        "
        name="menu"
      >
        <option value="home">Home</option>
        <option value="event">Event</option>
        <option value="accesories">Accesories</option>
        <option value="apparel">Apparel</option>
        <option value="parrot">Featured Items</option>
      </select>
    </div>
  </header>
</template>

<script>
export default {
  name: "NavBar",
  data() {
    return {
      open: false,
    };
  },
  components: {},
  props: {},
  methods: {
    openShoppingList() {
      this.open = !this.open;
      this.$emit("openModal", this.open);
    },
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped></style>
