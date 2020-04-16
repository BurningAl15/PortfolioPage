<template>
  <div class="w-9/12 mx-auto text-center">
    <h1 class="text-white text-6xl pt-10">
      Aldhair Vera
      <br />Camacho
    </h1>
    <h2 class="text-red-600 text-4xl pt-6">
      <i>Game Developer and Front-End Developer</i>
    </h2>
    <p class="text-white text-4xl pt-6">
      Computer Science Student
      <br />Unity3D / C# / VR
      <br />HTML / CSS / React JS / Vue JS
    </p>
    <SocialMediaBar/>
  </div>
</template>

<script>
import SocialMediaBar from "./SocialMedia";

export default {
  name: "Hero",
  components: { SocialMediaBar }
};
</script>

<style lang="scss" scoped>
</style>