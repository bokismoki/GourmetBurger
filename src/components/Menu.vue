<template>
  <section class="menu py-12 lg:px-24">
    <div class="md:flex md:mb-16 md:items-center">
      <div class="md:w-1/2">
        <h1 class="font-GreatVibes text-mainGolden text-center text-3xl md:text-right">Review</h1>
        <h1 class="font-PTSerif text-center text-2xl font-bold -mt-1 md:text-right">Our Full Menu</h1>
      </div>
      <p
        class="font-Lato text-center my-20 font-bold md:text-left md:w-1/2 md:my-0 md:ml-16"
      >Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse varius enim in eros elementum tristique. Duis cursus.</p>
    </div>
    <div class="md:flex">
      <div class="relative max-w-lg mx-auto md:w-1/2">
        <img class="relative z-20 h-64 mx-auto" src="@/assets/img/fries.png" alt="Fries" />
        <img
          class="z-10 h-40 absolute top-0 left-0 md:hidden"
          src="@/assets/img/scattered-salt.png"
          alt="Scattered Salt"
        />
        <img
          class="z-10 h-40 absolute bottom-0 right-0"
          src="@/assets/img/scattered-salt.png"
          alt="Scattered Salt"
        />
      </div>
      <div class="mt-8 md:w-1/2 text-center md:text-left md:ml-16">
        <h1 class="font-GreatVibes text-mainGolden text-3xl">Appetizers</h1>
        <p
          class="font-Lato"
        >Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse varius enim in eros elementum</p>
      </div>
    </div>
    <div class="md:flex md:mt-10">
      <div class="my-20 md:w-1/2 text-center md:text-left">
        <h1 class="font-GreatVibes text-mainGolden text-3xl">Main Dishes</h1>
        <p
          class="font-Lato"
        >Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse varius</p>
      </div>
      <div class="relative max-w-lg mx-auto md:w-1/2">
        <img class="relative z-20 h-64 mx-auto" src="@/assets/img/main-meal.png" alt="Main Meal" />
        <img
          class="z-10 h-40 absolute top-0 right-0"
          src="@/assets/img/scattered-salt.png"
          alt="Scattered Salt"
        />
        <img
          class="z-10 h-40 absolute bottom-0 left-0"
          src="@/assets/img/scattered-pepper.png"
          alt="Scattered Pepper"
        />
      </div>
    </div>
    <div class="md:flex">
      <div class="relative max-w-lg mx-auto mt-20 md:w-1/2">
        <img class="relative z-20 h-64 mx-auto" src="@/assets/img/salad.png" alt="Salad" />
        <img
          class="z-10 h-40 absolute bottom-0 right-0"
          src="@/assets/img/scattered-salt.png"
          alt="Scattered Salt"
        />
        <img
          class="z-10 h-40 absolute top-0 left-0"
          src="@/assets/img/scattered-salt.png"
          alt="Scattered Salt"
        />
      </div>
      <div class="my-20 md:w-1/2 text-center md:ml-16 md:text-left">
        <h1 class="font-GreatVibes text-mainGolden text-3xl">Side Dishes</h1>
        <p
          class="font-Lato"
        >Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse varius enim in eros elementum</p>
      </div>
    </div>
    <div class="md:flex">
      <div class="my-20 md:w-1/2 text-center md:text-left">
        <h1 class="font-GreatVibes text-mainGolden text-3xl">Desserts</h1>
        <p
          class="font-Lato"
        >Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse varius</p>
      </div>
      <div class="relative max-w-lg mx-auto mt-20 md:w-1/2">
        <img class="relative z-20 h-64 mx-auto" src="@/assets/img/dessert.png" alt="Dessert" />
        <img
          class="z-10 h-64 absolute top-0 left-0"
          src="@/assets/img/scattered-pepper.png"
          alt="Scattered Pepper"
        />
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Menu"
};
</script>

<style lang="scss" scoped>
</style>