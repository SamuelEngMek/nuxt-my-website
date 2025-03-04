<template>
    <figure class="p-6">
      <img 
        class="rounded-full mx-auto object-cover" 
        :src="photo" 
        alt="profile picture"
        style="width: 128px; height: 128px; object-fit: cover;" 
      />
      <figure class="pt-6 text-center space-y-4">
        <figcaption class="font-medium">
          <div class="text-white text-xl">{{ title }}</div>
          <div class="text-gray-100 font-light">{{ subtitle }}</div>
        </figcaption>
        <blockquote>
          <p class="text-white font-medium">{{ headline }}</p>
        </blockquote>
      </figure>
    </figure>
  </template>
  
  <script setup>
    const { photo, title, subtitle, headline } = defineProps(['photo','title', 'subtitle', 'headline']);
  </script>
  