<template>
  <!-- <app-header />
  <router-view /> -->
  <div class="high-specificity">
    <div class="nested">
      <!-- Will be red-500 -->
      <div class="selector text-red-500">Hello</div>
    </div>
  </div>

  <!-- Will be #bada55 -->
  <div class="text-red-500" style="color: #bada55;">World</div>
</template>

<script>
// import AppHeader from "@/components/AppHeader.vue";

export default {
  name: "App",
  components: {
    // AppHeader,
  },
};
</script>

<style></style>
