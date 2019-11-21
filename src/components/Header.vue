<template>
  <header class="py-6 sticky z-50 bg-mainBlack top-0 flex items-center justify-between">
    <img class="w-44 cursor-pointer" src="@/assets/img/logo.png" alt="Logo Image" />
    <div class="cursor-pointer inline-block flex item-center">
      <CartSVG />
      <span class="font-bold ml-3 text-xs text-mainGolden">0</span>
    </div>
    <div class="cursor-pointer inline-block lg:hidden">
      <div class="bg-white w-8" style="height: 1px;"></div>
      <div class="bg-white w-5 mt-2" style="height: 1px;"></div>
      <div class="bg-white w-8 mt-2" style="height: 1px;"></div>
    </div>
    <div class="hidden lg:flex lg:items-center">
      <a href="#">About</a>
      <a class="ml-5 inline-block py-1 px-2 text-sm font-medium font-Lato" href="#">Menu</a>
      <a class="ml-5 inline-block py-1 px-2 text-sm font-medium font-Lato" href="#">Events</a>
      <a class="ml-5 inline-block py-1 px-2 text-sm font-medium font-Lato" href="#">Press</a>
      <a class="ml-5 inline-block py-1 px-2 text-sm font-medium font-Lato" href="#">Careers</a>
      <a class="ml-5 inline-block py-1 px-2 text-sm font-medium font-Lato" href="#">Contact</a>
      <a class="ml-5 inline-block py-2 px-5 text-sm font-medium font-Lato border-mainGolden border-2" href="#">Reserve a Table</a>
    </div>
  </header>
</template>

<script>
import CartSVG from "@/components/CartSVG";

export default {
  name: "Header",
  components: {
    CartSVG
  }
};
</script>

<style lang="scss" scoped>
</style>