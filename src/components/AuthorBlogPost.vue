<template>
  <article class="blog-post">
    <h2 class="self-start uppercase tracking-[3px]">{{ category }}</h2>
    <h3 class="self-start mt-5 text-4xl font-bold tracking-tighter leading-10 text-gray-800 max-md:max-w-full">
      {{ title }}
    </h3>
    <p class="mt-4 leading-7 text-zinc-500 max-md:max-w-full">
      {{ description }}
    </p>
  </article>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'BlogPost',
  props: {
    category: {
      type: String,
      required: true,
    },
    title: {
      type: String,
      required: true,
    },
    description: {
      type: String,
      required: true,
    },
  },
});
</script>
