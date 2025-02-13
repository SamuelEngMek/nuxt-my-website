<template>
    <figure class="p-6">
        <img 
        class="w-32 h-32 rounded-full mx-auto" 
        :src="photo" 
        alt="profile picture" 
        width="400"
        height="400"
    />
        <figure class="pt-6 text-center space-y-4">
        <figcaption class="font-medium">
            <div class="text-white text-xl">{{ title }}</div>
            <div class="text-gray-100 font-light">{{subtitle}}</div>
        </figcaption>
        <blockquote>
            <p class="text-white font-medium">{{headline}}</p>
        </blockquote>
        </figure>
    </figure>
</template>

<script setup>
    const { photo, title, subtitle, headline } = defineProps(['photo','title', 'subtitle', 'headline']);
</script>