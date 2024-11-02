<template>
  <!-- Featured Post -->
  <section class="bg-white px-[80px] py-[128px] flex col md:flex-row justify-between gap-8">
    <!-- Featured Post Section -->
    <div class="h-[804px] flex flex-col gap-4">
      <h2 class="text-x-black text-4xl font-bold leading-[48px] tracking-[-2px]">Featured Post</h2>
      <div class="w-full flex-grow border p-8">
        <img class="w-full object-cover mb-8" :src="featuredImage" alt="Featured Building" />
        <div class="w-full flex flex-col gap-4">
          <label class="text-x-black text-sm font-medium leading-[20px]">
            By <span class="text-x-yellow">{{ featuredAuthor }}</span> &nbsp;|&nbsp; {{ featuredDate }}
          </label>
          <h3 class="text-x-black text-3xl font-bold leading-[40px] tracking-[-1px]">
            {{ featuredTitle }}
          </h3>
          <p class="text-x-mediumgrey w-[551px] leading-[28px] mb-4">
            {{ featuredDescription }}
          </p>
          <a href="/blog" class="w-[204px] flex items-center justify-center bg-x-blue px-[48px] py-[16px] text-white font-bold hover:bg-x-yellow transition duration-150 ease-in-out">
            Read More &gt;
          </a>
        </div>
      </div>
    </div>

    <!-- All Posts Section -->
    <div class="h-[804px] flex flex-col gap-4">
      <div class="flex items-center justify-between">
        <h2 class="text-x-black text-4xl font-bold leading-[48px] tracking-[-2px]">All Posts</h2>
        <a href="#" class="text-x-yellow leading-[28px]">View All</a>
      </div>
      <div v-for="(post, index) in allPosts" :key="index" class="w-[517px] h-[181px] flex flex-col justify-center p-8 gap-2 hover:bg-x-lightyellow hover:cursor-pointer transition duration-200 ease-in-out">
        <label class="text-x-black text-sm font-medium leading-[20px]">
          By <span class="text-x-yellow">{{ post.author }}</span> &nbsp;|&nbsp; {{ post.date }}
        </label>
        <h4 class="text-x-black text-2xl font-bold leading-[32px] w-[369px]">
          {{ post.title }}
        </h4>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts">
import { ref } from 'vue';

import featuredImage from '@/assets/images/misc/white-building.png';
const featuredAuthor = ref('John Doe');
const featuredDate = ref('May 23, 2022');
const featuredTitle = ref('Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor.');
const featuredDescription = ref('Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident.');

const allPosts = ref([
  {
    author: 'John Doe',
    date: 'Aug 23, 2021',
    title: '8 Figma design systems that you can download for free today.',
  },
  {
    author: 'John Doe',
    date: 'Aug 23, 2021',
    title: '8 Figma design systems that you can download for free today.',
  },
  {
    author: 'John Doe',
    date: 'Aug 23, 2021',
    title: '8 Figma design systems that you can download for free today.',
  },
  {
    author: 'John Doe',
    date: 'Aug 23, 2021',
    title: '8 Figma design systems that you can download for free today.',
  },
  // Add additional posts here
]);
</script>

<style scoped>
/* Add custom styles here if needed */
</style>
