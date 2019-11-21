<template>
  <section class="pre-footer my-10 py-40 bg-center bg-cover" :style="{backgroundImage: 'url(' + image + ')'}">
    <div class="text-center my-8">
      <a class="bg-mainGolden inline-block font-semibold tracking-wider py-3 px-8" href="#">Discover the Menu ↠</a>
    </div>
    <div class="bg-mainGolden w-1/6 mx-auto" style="height: 1px;"></div>
    <div class="text-center my-8">
      <a class="bg-mainGolden inline-block font-semibold tracking-wider py-3 px-8" href="#">Book Your Table ↠</a>
    </div>
  </section>
</template>

<script>
export default {
  name: "PreFooter",
  data() {
      return {
          image: require('@/assets/img/pre-footer-bg.jpg')
      }
  }
};
</script>

<style lang="scss" scoped>

</style>