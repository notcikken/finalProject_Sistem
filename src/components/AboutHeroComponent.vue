<template>
  <section class="flex overflow-hidden flex-col px-20 py-16 bg-white  ">
    <section class="z-10 self-end mr-10 pt w-full max-w-[1133px]  absolute">
      <div class="flex gap-5">
        <div class="flex flex-col w-[57%]">
          <h1 class="grow px-16 pt-24 pb-16 w-full text-5xl font-bold tracking-tighter text-gray-800 bg-white leading-[64px]">
            We are a team of content writers who share their learnings
          </h1>
        </div>
        <div class="flex flex-col ml-5 w-[43%]">
          <p class="self-stretch my-auto text-base leading-7 text-neutral-600">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
          </p>
        </div>
      </div>
    </section>
    <section class="mt-64">
      <div class="flex relative flex-col items-start px-20 pt-[444px] min-h-[444px] ">
      <img loading="lazy" src="https://cdn.builder.io/api/v1/image/assets/TEMP/49fcdacd4ac5f011a95636ead2e310f12f7436f31f42a97d46944a344b04390f?placeholderIfAbsent=true&apiKey=ed89e008b7de47e5a3187e8a4c1c72f3" alt="" class="object-cover absolute inset-0 size-full" />
      <div class="flex relative flex-col max-w-full w-[862px]">
        <div class="px-12 py-8 max-w-full bg-blue-600 w-[630px]">
          <div class="flex gap-5">
            <div class="flex flex-col w-[33%]">
              <div class="flex flex-col grow text-white">
                <p class="self-start text-6xl font-bold tracking-tighter leading-none">12+</p>
                <p class="text-base leading-7">Blogs Published</p>
              </div>
            </div>
            <div class="flex flex-col ml-5 w-[33%]">
              <div class="flex flex-col grow text-white">
                <p class="self-start text-6xl font-bold tracking-tighter leading-none">18K+</p>
                <p class="text-base leading-7">Views on Finsweet</p>
              </div>
            </div>
            <div class="flex flex-col ml-5 w-[33%]">
              <div class="flex flex-col grow text-white">
                <p class="text-6xl font-bold tracking-tighter leading-none">30K+</p>
                <p class="text-base leading-7">Total active Users</p>
              </div>
            </div>
          </div>
        </div>
        <div class="flex flex-wrap gap-px">
          <div class="flex shrink-0 max-w-full bg-amber-300 h-[23px] w-[750px]"></div>
        </div>
      </div>
    </div>
    <section class="flex flex-col justify-center items-start px-16 py-40 w-full bg-gray-100">
      <div class="mb-0 max-w-full w-[883px]">
        <div class="flex gap-5">
          <div class="flex flex-col w-6/12">
            <div class="flex flex-col grow text-gray-800">
              <h2 class="self-start text-base font-semibold leading-none uppercase tracking-[3px]">Our mission</h2>
              <p class="mt-6 text-3xl font-bold tracking-tighter leading-10">Creating valuable content for creatives all around the world</p>
            </div>
          </div>
          <div class="flex flex-col ml-5 w-6/12">
            <div class="flex flex-col grow text-gray-800">
              <h2 class="self-start text-base font-semibold leading-none uppercase tracking-[3px]">Our Vision</h2>
              <p class="mt-6 text-3xl font-bold tracking-tighter leading-10">A platform that empowers individuals to improve</p>
            </div>
          </div>
        </div>
      </div>
    </section>
    </section>
  </section>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'AboutHeroComponent',
});
</script>
