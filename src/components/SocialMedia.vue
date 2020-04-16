<template>
  <div>
    <h2 class="text-white text-4xl pt-10">Find me on</h2>
    <div class="flex justify-center h-8 mt-10 h-12">
      <a class="mx-4" href="/" alt="...">
        <img class="h-24 w-24" :src="facebookImage" />
      </a>
      <a class="mx-4" href="/" alt="...">
        <img class="h-24 w-24" :src="facebookImage" />
      </a>
      <a class="mx-4" href="/" alt="...">
        <img class="h-24 w-24" :src="facebookImage" />
      </a>
      <a class="mx-4" href="/" alt="...">
        <img class="h-24 w-24" :src="facebookImage" />
      </a>
          <a class="mx-4" href="/" alt="...">
        <img class="h-24 w-24" :src="facebookImage" />
      </a>
      <a class="mx-4" href="/" alt="...">
        <img class="h-24 w-24" :src="facebookImage" />
      </a>
    </div>
  </div>
</template>
<script>
import facebookImage from "../Image/SocialNetwork/Facebook.svg";
export default {
  data: function() {
    return {
      facebookImage
    };
  }
};
</script>

<style lang="scss" scoped>
</style>