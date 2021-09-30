<template>
  <section>
    <Carousel class="sm:hidden" />
    <!-- Text section -->
    <div class="p-1">
      <h2 class="text-left text-2xl sm:p-1 sm:m-5 m-1">Intro Copy Headline</h2>
      <p class="text-justify sm:p-1 sm:m-5 sm:text-sm m-1">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Tenetur, harum
        blanditiis voluptates quis quas ea ipsum? Necessitatibus reprehenderit
        vitae ipsam aperiam laborum natus ratione, unde quo modi, atque,
        voluptatibus repudiandae? Lorem ipsum dolor sit amet consectetur
        adipisicing elit. Distinctio inventore dolore blanditiis incidunt quo
        autem ratione dolorum repudiandae, nemo delectus minus porro voluptatum
        ad itaque iure quae eos est neque?
      </p>
    </div>
    <!-- Several Items section -->
    <div class="max-w-full flex flex-wrap justify-around sm:m-5 m-1 text-left">
      <div class="flex flex-col w-1/4 sm:w-1/2 p-1">
        <img src="https://picsum.photos/300" alt="" class="" />
        <h1>Title</h1>
        <p class="text-sm">Category</p>
        <p class="text-sm">$88</p>
      </div>
      <div class="flex flex-col w-1/4 sm:w-1/2 p-1">
        <img src="https://picsum.photos/300" alt="" class="" />
        <h1>Title</h1>
        <p class="text-sm">Category</p>
        <p class="text-sm">$88</p>
      </div>
      <div class="flex flex-col w-1/4 sm:w-1/2 p-1">
        <img src="https://picsum.photos/300" alt="" class="" />
        <h1>Title</h1>
        <p class="text-sm">Category</p>
        <p class="text-sm">$88</p>
      </div>
      <div class="flex flex-col w-1/4 sm:w-1/2 p-1">
        <img src="https://picsum.photos/300" alt="" class="" />
        <h1>Title</h1>
        <p class="text-sm">Category</p>
        <p class="text-sm">$88</p>
      </div>
    </div>
  </section>
</template>

<script>
import Carousel from "./Carousel.vue";
export default {
  name: "App",
  components: {
    Carousel,
  },
};
</script>

<style></style>
