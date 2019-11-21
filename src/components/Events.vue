<template>
  <section class="about md:flex md:mt-16 lg:justify-center">
    <div class="w-full h-64 md:w-2/5 lg:max-w-xl">
      <img
        class="px-5 w-full mt-5 relative h-full object-cover md:mt-0 md:p-0 md:ml-5 md:h-auto md:top-0 md:block md:-mt-10 md:max-h-full"
        src="@/assets/img/events.jpg"
        style="bottom: -2rem;"
        alt="People eating and drinking"
      />
    </div>
    <div class="bg-white p-5 pt-20 text-mainBlack md:w-3/5 text-center md:text-left md:p-10 lg:max-w-xl">
      <h1 class="font-GreatVibes text-mainGolden text-3xl">Discover</h1>
      <h1 class="font-PTSerif text-2xl font-bold -mt-1">Our Upcoming Events</h1>
      <p
        class="font-Lato mt-2"
      >Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse varius enim in eros elementum tristique. Duis cursus, mi quis viverra.</p>
      <a
        class="block mt-5 text-mainGolden uppercase text-sm font-semibold py-2"
        href="#"
      >See our upcoming events ↠</a>
    </div>
  </section>
</template>

<script>
export default {
  name: "About"
};
</script>

<style lang="scss" scoped>
</style>