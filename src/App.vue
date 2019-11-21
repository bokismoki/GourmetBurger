<template>
  <div id="app" class="px-5 bg-mainBlack text-white">
    <Header />
    <Hero />
    <About />
    <Menu />
    <Events />
    <PreFooter />
    <Footer />
  </div>
</template>

<script>
import Header from "@/components/Header";
import Hero from "@/components/Hero";
import About from "@/components/About";
import Menu from "@/components/Menu";
import Events from "@/components/Events";
import PreFooter from "@/components/PreFooter";
import Footer from "@/components/Footer";

export default {
  name: "app",
  components: {
    Header,
    Hero,
    About,
    Menu,
    Events,
    PreFooter,
    Footer
  }
};
</script>

<style lang="scss">
*,
*::before,
*::after {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
body {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen,
    Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
}
</style>
