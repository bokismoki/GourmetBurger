<template>
  <footer class="lg:px-10">
    <div class="lg:flex lg:flex-row-reverse lg:start lg:justify-between">
      <div>
        <img class="w-24 mx-auto cursor-pointer" src="@/assets/img/logo-initials.png" alt="Logo" />
        <p class="font-Lato text-center text-sm mt-3">info@gourmetburger.com</p>
        <div class="flex items-center justify-center mt-3">
          <img class="w-4 cursor-pointer" src="@/assets/img/facebook.png" alt="Facebook Logo" />
          <img
            class="w-4 mx-6 cursor-pointer"
            src="@/assets/img/instagram.png"
            alt="Instagram Logo"
          />
          <img class="w-4 cursor-pointer" src="@/assets/img/twitter.png" alt="Twitter Logo" />
        </div>
      </div>
      <div class="mt-16 text-center lg:mt-0">
        <h3 class="font-PTSerif text-mainGolden text-lg lg:text-left">Opening Hours</h3>
        <div class="mt-5 font-Lato lg:flex lg:items-center">
          <p class="text-sm">Monday-Friday</p>
          <p class="mt-1 lg:mt-0">10am-11pm</p>
        </div>
        <div class="mt-5 font-Lato lg:flex lg:items-center">
          <p class="text-sm">Saturday</p>
          <p class="mt-1 lg:mt-0">10am-12pm</p>
        </div>
        <div class="mt-5 font-Lato lg:flex lg:items-center">
          <p class="text-sm">Sunday</p>
          <p class="mt-1 lg:mt-0">10am-10pm</p>
        </div>
      </div>
      <div class="mt-16 text-center lg:mt-0">
        <h3 class="font-PTSerif text-mainGolden text-lg lg:text-left">Locations</h3>
        <div class="md:flex md:justify-center">
          <div class="mt-5 font-Lato md:mx-10 lg:mx-5 lg:ml-0 lg:text-left">
            <p>NYC</p>
            <p class="mt-1 text-sm lg:mt-2">2227 West Main St</p>
            <p class="mt-1 text-sm lg:mt-2">New York, NY 3009</p>
            <p class="mt-1 text-sm lg:mt-2">555-876-566</p>
            <p class="mt-1 text-sm lg:mt-2">nyc@gourmetburger.com</p>
          </div>
          <div class="mt-5 font-Lato md:mx-10 lg:mx-5 lg:ml-0 lg:text-left">
            <p>Dallas</p>
            <p class="mt-1 text-sm lg:mt-2">35 Hoffman Rd</p>
            <p class="mt-1 text-sm lg:mt-2">Dallas, TX 3887</p>
            <p class="mt-1 text-sm lg:mt-2">555-876-566</p>
            <p class="mt-1 text-sm lg:mt-2">tx@gourmetburger.com</p>
          </div>
          <div class="mt-5 font-Lato md:mx-10 lg:mx-5 lg:ml-0 lg:text-left">
            <p>Los Angeles</p>
            <p class="mt-1 text-sm lg:mt-2">22 Boulevard Ave</p>
            <p class="mt-1 text-sm lg:mt-2">Los Angeles, CA 3221</p>
            <p class="mt-1 text-sm lg:mt-2">555-876-566</p>
            <p class="mt-1 text-sm lg:mt-2">la@gourmetburger.com</p>
          </div>
        </div>
      </div>
    </div>
    <div class="mt-16 py-5 border-t-2 border-blue-900">
      <p
        class="font-Lato text-sm text-center"
      >Created by Rebecca Marion Desing | Powered by Webflow | Image Licensing | Style Guide</p>
    </div>
  </footer>
</template>

<script>
export default {
  name: "Footer"
};
</script>

<style lang="scss" scoped>
</style>