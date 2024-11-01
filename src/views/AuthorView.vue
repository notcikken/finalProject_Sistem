<script setup lang="ts">

import AuthorHeader from '@/components/AuthorHeader.vue';
import AuthorPost from '@/components/AuthorPost.vue';
import MainLayout from '@/layouts/MainLayout.vue'
</script>

<template>
  <MainLayout>
    <AuthorHeader/>
    <div class="px-[256px] py-[128px] ">
      <AuthorPost />
    </div>
    
  </MainLayout>
</template>
