<template>
  <div id="app" class="bg-gray-900 w-full h-screen">
    <NavBar />
    <Hero />
  </div>
</template>

<script>
import NavBar from "./components/NavBar";
import Hero from "./components/Hero";

export default {
  name: "App",
  components: { NavBar, Hero }
};
</script>

<style>
</style>
