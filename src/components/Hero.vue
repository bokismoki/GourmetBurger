<template>
  <section class="hero lg:flex items-end lg:py-20">
    <div class="py-12 lg:w-1/2 text-center lg:text-left lg:pl-10">
      <h1
        class="text-4xl font-semibold font-PTSerif max-w-sm mx-auto lg:mx-0 lg:max-w-full lg:text-5xl"
      >Gourmet. The way burgers should be.</h1>
      <p
        class="font-Lato md:w-5/6 md:mx-auto lg:w-full lg:mx-0"
      >Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation.</p>
      <div class="mt-8">
        <a
          href="#"
          class="bg-mainGolden font-PTSerif inline-block py-3 px-8 tracking-wider lg:bg-transparent lg:border-2 lg:border-mainGolden"
        >Book Online</a>
      </div>
    </div>
    <div class="relative max-w-lg mx-auto lg:w-1/2">
      <img class="relative z-20 h-64 mx-auto lg:w-full lg:h-full" src="@/assets/img/burger.png" alt="Burger" />
      <img class="z-10 h-56 absolute top-0 left-0" src="@/assets/img/scattered-pepper.png" alt="Scattered Pepper" />
      <img class="z-10 h-40 absolute bottom-0 right-0" src="@/assets/img/scattered-salt.png" alt="Scattered Salt" />
    </div>
  </section>
</template>

<script>
export default {
  name: "Hero"
};
</script>

<style lang="scss" scoped>
</style>