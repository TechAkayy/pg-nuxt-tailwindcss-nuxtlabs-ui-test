<script setup lang="ts">
  // const props = defineProps({
  // 	name: {
  // 		type: String,
  // 		default: 'TheFooter',
  // 	},
  // })
</script>
<template>
  <div class="pb-24 pt-12">
    <div class="container mx-auto px-8">
      <div class="flex flex-wrap justify-center space-x-8">
        <NuxtLink
          href="https://www.facebook.com/vuedesigner/"
          aria-label="facebook"
          external
          target="_blank"
        >
          <UIcon name="i-logos-facebook" class="text-2xl"></UIcon>
        </NuxtLink>
        <NuxtLink
          href="https://twitter.com/vuedesigner/"
          aria-label="twitter"
          external
          target="_blank"
        >
          <UIcon name="i-logos-twitter" class="text-2xl"></UIcon>
        </NuxtLink>
        <NuxtLink
          href="https://forum.pinegrow.com/c/vue-designer"
          aria-label="discourse"
          external
          target="_blank"
        >
          <UIcon name="i-logos-discourse-icon" class="text-2xl"></UIcon>
        </NuxtLink>
        <NuxtLink
          href="https://www.youtube.com/@pgvuedesigner/"
          aria-label="youtube"
          external
          target="_blank"
        >
          <UIcon name="i-logos-youtube-icon" class="text-2xl"></UIcon>
        </NuxtLink>
      </div>
    </div>
  </div>
</template>
<style scoped></style>
