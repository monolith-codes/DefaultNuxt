<template>
  <div class="TestDiv"></div>
</template>

<script setup lang="ts">
definePageMeta({
  layout: "default",
});

useSeoMeta({
  title: "Test Site | Home",
  ogTitle: "Test Site | Home",
  description: "TEST SITE LONGET TEXT!",
  ogDescription: "TEST SITE LONGET TEXT!",
  ogImage: "https://testlink",
  twitterCard: "summary_large_image",
});
</script>

<style lang="scss">
body {
  margin: 0px;
  padding: 0px;
}

.TestDiv {
  height: 100vh;
}
</style>
