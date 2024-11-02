<template>
  <section class="flex overflow-hidden flex-col px-20 py-20 bg-white max-md:px-5">
    <div class="max-md:max-w-full">
      <div class="flex gap-5 max-md:flex-col">
        <article class="flex flex-col w-[43%] max-md:ml-0 max-md:w-full">
          <div class="flex flex-col self-stretch my-auto font-bold text-gray-800 max-md:mt-10 max-md:max-w-full">
            <h2 class="self-start text-4xl tracking-tighter leading-none text-gray-800">
              Our team of creatives
            </h2>
            <p class="mt-4 text-2xl leading-8 max-md:max-w-full">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt.
            </p>
            <p class="mt-4 text-base leading-7 max-md:max-w-full">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat.
            </p>
          </div>
        </article>
        <div class="flex flex-col ml-5 w-[57%] max-md:ml-0 max-md:w-full">
          <img loading="lazy" src="https://cdn.builder.io/api/v1/image/assets/TEMP/7d3421017c6a0c2256159a152ba36acc45d3b4a6b36c073d3ae43ec5e36dea1a?placeholderIfAbsent=true&apiKey=ed89e008b7de47e5a3187e8a4c1c72f3" alt="Our team of creatives" class="object-contain grow w-full rounded-none aspect-[1.42] max-md:mt-10 max-md:max-w-full" />
        </div>
      </div>
    </div>
    <div class="mt-32 w-full max-w-[1207px] max-md:mt-10 max-md:max-w-full">
      <div class="flex gap-5 max-md:flex-col">
        <div class="flex flex-col w-[55%] max-md:ml-0 max-md:w-full">
          <img loading="lazy" src="https://cdn.builder.io/api/v1/image/assets/TEMP/395f138cdfcf52ffb822fbc43cc2080e0d7b514281c46704e661adb2ceaf6294?placeholderIfAbsent=true&apiKey=ed89e008b7de47e5a3187e8a4c1c72f3" alt="Why we started this Blog" class="object-contain grow w-full aspect-[1.21] max-md:mt-10 max-md:max-w-full" />
        </div>
        <article class="flex flex-col ml-5 w-[45%] max-md:ml-0 max-md:w-full">
          <div class="flex flex-col self-stretch my-auto font-bold text-gray-800 max-md:mt-10 max-md:max-w-full">
            <h2 class="self-start text-4xl tracking-tighter leading-none text-gray-800">
              Why we started this Blog
            </h2>
            <p class="mt-4 text-2xl leading-8 max-md:mr-2 max-md:max-w-full">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt.
            </p>
            <p class="mt-4 text-base leading-7 max-md:max-w-full">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat.
            </p>
          </div>
        </article>
      </div>
    </div>
  </section>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'AuthorValueContent',
});
</script>