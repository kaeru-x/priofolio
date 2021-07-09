<template>
  <div>
    <h1 class="text-center text-3xl py-2 fixed bg-white block w-full">priofolio</h1>
    <Gallery />
    <div class="w-full flex items-center">
      <button class="w-48 text-xl bg-gray-200 my-6 py-2 mx-auto ml-auto">
        More
      </button>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from "vue";
import Gallery from "~/components/Gallery.vue";

export default Vue.extend({
  components: { Gallery },});
</script>
