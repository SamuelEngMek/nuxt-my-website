<template>
    <figure class="pt-32 text-center">
        <h2 class="text-lg md:text-xl font-semibold text-white mb-2">Tecnologias & Frameworks</h2>

      <div class="mx-auto w-3/4 md:w-1/2 bg-gray-900 py-4 rounded-lg overflow-hidden">
        <div class="relative w-full overflow-hidden">
          
          <div class="flex items-center animate-marquee">
            <div class="flex items-center space-x-10" v-for="n in 2" :key="n">
              <img 
                v-for="(stack, index) in stacks" 
                :key="index + '-loop-' + n" 
                :src="stack.logo" 
                :alt="stack.name"
                class="h-16 w-auto object-contain"
              />
            </div>
          </div>
        </div>
      </div>
    </figure>
  </template>
  
  <script setup>
  const { stacks } = defineProps({
    stacks: {
      type: Array,
      required: true,
    }
  });
  </script>
  
  <style>
  @keyframes marquee {
    0% { transform: translateX(0); }
    100% { transform: translateX(-50%); } 
  }
  
  .animate-marquee {
    display: flex;
    animation: marquee 25s linear infinite;
    width: max-content; 
  }
  </style>
  