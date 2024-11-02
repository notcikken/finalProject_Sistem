<script setup lang="ts">
import AboutHeroComponent from '@/components/AboutHeroComponent.vue';
import AboutValueContent from '@/components/AboutValueContent.vue';
import JoinContent from '@/components/JoinContent.vue';
import MainLayout from '@/layouts/MainLayout.vue'
</script>

<template>
  <MainLayout>
    <AboutHeroComponent />
    <AboutValueContent />
    <!-- List Author -->
    <section class="flex flex-col gap-8 bg-white px-[80px] py-[40px]">
        <h2 class="text-x-black text-4xl text-center font-bold leading-[48px] tracking-[-2px]">List of Authors</h2>
        <div class="flex items-center justify-between gap-6">
          <div class="w-[296px] bg-x-lightgrey flex flex-col items-center justify-center gap-4 p-6 hover:bg-x-lightyellow hover:cursor-pointer transition duration-200 ease-in-out">
            <img src="@/assets/images/misc/author-1.png" alt="Author 1" class="w-[128px] h-[128px]">
            <div class="flex flex-col items-center">
              <h3 class="text-x-black text-3xl font-bold leading-[40px] tracking-[-1px]">Floyd Miles</h3>
              <p class="text-x-mediumgrey leading-[28px] group-hover:text-white transition duration-200 ease-in-out">Content Writer @Company</p>
            </div>
            <ul class="flex items-center gap-6">
              <li>
                <a href="#">
                  <img src="@/assets/images/logo/facebook.png" alt="" class="hover:opacity-75 transition duration-150 ease-in-out">
                </a>
              </li>
              <li>
                <a href="#">
                  <img src="@/assets/images/logo/twitter.png" alt="" class="hover:opacity-75 transition duration-150 ease-in-out">
                </a>
              </li>
              <li>
                <a href="#">
                  <img src="@/assets/images/logo/instagram.png" alt="" class="hover:opacity-75 transition duration-150 ease-in-out">
                </a>
              </li>
              <li>
                <a href="#">
                  <img src="@/assets/images/logo/linkedin.png" alt="" class="hover:opacity-75 transition duration-150 ease-in-out">
                </a>
              </li>
            </ul>
          </div>
          <div class="w-[296px] bg-x-lightgrey flex flex-col items-center justify-center gap-4 p-6 hover:bg-x-lightyellow hover:cursor-pointer transition duration-200 ease-in-out">
            <img src="@/assets/images/misc/author-2.png" alt="Author 1" class="w-[128px] h-[128px]">
            <div class="flex flex-col items-center">
              <h3 class="text-x-black text-3xl font-bold leading-[40px] tracking-[-1px]">Dianne Russell</h3>
              <p class="text-x-mediumgrey leading-[28px] group-hover:text-white transition duration-200 ease-in-out">Content Writer @Company</p>
            </div>
            <ul class="flex items-center gap-6">
              <li>
                <a href="#">
                  <img src="@/assets/images/logo/facebook.png" alt="" class="hover:opacity-75 transition duration-150 ease-in-out">
                </a>
              </li>
              <li>
                <a href="#">
                  <img src="@/assets/images/logo/twitter.png" alt="" class="hover:opacity-75 transition duration-150 ease-in-out">
                </a>
              </li>
              <li>
                <a href="#">
                  <img src="@/assets/images/logo/instagram.png" alt="" class="hover:opacity-75 transition duration-150 ease-in-out">
                </a>
              </li>
              <li>
                <a href="#">
                  <img src="@/assets/images/logo/linkedin.png" alt="" class="hover:opacity-75 transition duration-150 ease-in-out">
                </a>
              </li>
            </ul>
          </div>
          <div class="w-[296px] bg-x-lightgrey flex flex-col items-center justify-center gap-4 p-6 hover:bg-x-lightyellow hover:cursor-pointer transition duration-200 ease-in-out">
            <img src="@/assets/images/misc/author-3.png" alt="Author 1" class="w-[128px] h-[128px]">
            <div class="flex flex-col items-center">
              <h3 class="text-x-black text-3xl font-bold leading-[40px] tracking-[-1px]">Jenny Wilson</h3>
              <p class="text-x-mediumgrey leading-[28px] group-hover:text-white transition duration-200 ease-in-out">Content Writer @Company</p>
            </div>
            <ul class="flex items-center gap-6">
              <li>
                <a href="#">
                  <img src="@/assets/images/logo/facebook.png" alt="" class="hover:opacity-75 transition duration-150 ease-in-out">
                </a>
              </li>
              <li>
                <a href="#">
                  <img src="@/assets/images/logo/twitter.png" alt="" class="hover:opacity-75 transition duration-150 ease-in-out">
                </a>
              </li>
              <li>
                <a href="#">
                  <img src="@/assets/images/logo/instagram.png" alt="" class="hover:opacity-75 transition duration-150 ease-in-out">
                </a>
              </li>
              <li>
                <a href="#">
                  <img src="@/assets/images/logo/linkedin.png" alt="" class="hover:opacity-75 transition duration-150 ease-in-out">
                </a>
              </li>
            </ul>
          </div>
          <div class="w-[296px] bg-x-lightgrey flex flex-col items-center justify-center gap-4 p-6 hover:bg-x-lightyellow hover:cursor-pointer transition duration-200 ease-in-out">
            <img src="@/assets/images/misc/author-4.png" alt="Author 1" class="w-[128px] h-[128px]">
            <div class="flex flex-col items-center">
              <h3 class="text-x-black text-3xl font-bold leading-[40px] tracking-[-1px]">Leslie Alexander</h3>
              <p class="text-x-mediumgrey leading-[28px] group-hover:text-white transition duration-200 ease-in-out">Content Writer @Company</p>
            </div>
            <ul class="flex items-center gap-6">
              <li>
                <a href="#">
                  <img src="@/assets/images/logo/facebook.png" alt="" class="hover:opacity-75 transition duration-150 ease-in-out">
                </a>
              </li>
              <li>
                <a href="#">
                  <img src="@/assets/images/logo/twitter.png" alt="" class="hover:opacity-75 transition duration-150 ease-in-out">
                </a>
              </li>
              <li>
                <a href="#">
                  <img src="@/assets/images/logo/instagram.png" alt="" class="hover:opacity-75 transition duration-150 ease-in-out">
                </a>
              </li>
              <li>
                <a href="#">
                  <img src="@/assets/images/logo/linkedin.png" alt="" class="hover:opacity-75 transition duration-150 ease-in-out">
                </a>
              </li>
            </ul>
          </div>
        </div>
        <div class="flex items-center justify-between gap-6">
          <div class="w-[296px] bg-x-lightgrey flex flex-col items-center justify-center gap-4 p-6 hover:bg-x-lightyellow hover:cursor-pointer transition duration-200 ease-in-out">
            <img src="@/assets/images/misc/author-5.png" alt="Author 1" class="w-[128px] h-[128px]">
            <div class="flex flex-col items-center">
              <h3 class="text-x-black text-3xl font-bold leading-[40px] tracking-[-1px]">Guy Hawkins</h3>
              <p class="text-x-mediumgrey leading-[28px] group-hover:text-white transition duration-200 ease-in-out">Content Writer @Company</p>
            </div>
            <ul class="flex items-center gap-6">
              <li>
                <a href="#">
                  <img src="@/assets/images/logo/facebook.png" alt="" class="hover:opacity-75 transition duration-150 ease-in-out">
                </a>
              </li>
              <li>
                <a href="#">
                  <img src="@/assets/images/logo/twitter.png" alt="" class="hover:opacity-75 transition duration-150 ease-in-out">
                </a>
              </li>
              <li>
                <a href="#">
                  <img src="@/assets/images/logo/instagram.png" alt="" class="hover:opacity-75 transition duration-150 ease-in-out">
                </a>
              </li>
              <li>
                <a href="#">
                  <img src="@/assets/images/logo/linkedin.png" alt="" class="hover:opacity-75 transition duration-150 ease-in-out">
                </a>
              </li>
            </ul>
          </div>
          <div class="w-[296px] bg-x-lightgrey flex flex-col items-center justify-center gap-4 p-6 hover:bg-x-lightyellow hover:cursor-pointer transition duration-200 ease-in-out">
            <img src="@/assets/images/misc/author-6.png" alt="Author 1" class="w-[128px] h-[128px]">
            <div class="flex flex-col items-center">
              <h3 class="text-x-black text-3xl font-bold leading-[40px] tracking-[-1px]">Eleanor Pena</h3>
              <p class="text-x-mediumgrey leading-[28px] group-hover:text-white transition duration-200 ease-in-out">Content Writer @Company</p>
            </div>
            <ul class="flex items-center gap-6">
              <li>
                <a href="#">
                  <img src="@/assets/images/logo/facebook.png" alt="" class="hover:opacity-75 transition duration-150 ease-in-out">
                </a>
              </li>
              <li>
                <a href="#">
                  <img src="@/assets/images/logo/twitter.png" alt="" class="hover:opacity-75 transition duration-150 ease-in-out">
                </a>
              </li>
              <li>
                <a href="#">
                  <img src="@/assets/images/logo/instagram.png" alt="" class="hover:opacity-75 transition duration-150 ease-in-out">
                </a>
              </li>
              <li>
                <a href="#">
                  <img src="@/assets/images/logo/linkedin.png" alt="" class="hover:opacity-75 transition duration-150 ease-in-out">
                </a>
              </li>
            </ul>
          </div>
          <div class="w-[296px] bg-x-lightgrey flex flex-col items-center justify-center gap-4 p-6 hover:bg-x-lightyellow hover:cursor-pointer transition duration-200 ease-in-out">
            <img src="@/assets/images/misc/author-7.png" alt="Author 1" class="w-[128px] h-[128px]">
            <div class="flex flex-col items-center">
              <h3 class="text-x-black text-3xl font-bold leading-[40px] tracking-[-1px]">Robert Fox</h3>
              <p class="text-x-mediumgrey leading-[28px] group-hover:text-white transition duration-200 ease-in-out">Content Writer @Company</p>
            </div>
            <ul class="flex items-center gap-6">
              <li>
                <a href="#">
                  <img src="@/assets/images/logo/facebook.png" alt="" class="hover:opacity-75 transition duration-150 ease-in-out">
                </a>
              </li>
              <li>
                <a href="#">
                  <img src="@/assets/images/logo/twitter.png" alt="" class="hover:opacity-75 transition duration-150 ease-in-out">
                </a>
              </li>
              <li>
                <a href="#">
                  <img src="@/assets/images/logo/instagram.png" alt="" class="hover:opacity-75 transition duration-150 ease-in-out">
                </a>
              </li>
              <li>
                <a href="#">
                  <img src="@/assets/images/logo/linkedin.png" alt="" class="hover:opacity-75 transition duration-150 ease-in-out">
                </a>
              </li>
            </ul>
          </div>
          <div class="w-[296px] bg-x-lightgrey flex flex-col items-center justify-center gap-4 p-6 hover:bg-x-lightyellow hover:cursor-pointer transition duration-200 ease-in-out">
            <img src="@/assets/images/misc/author-8.png" alt="Author 1" class="w-[128px] h-[128px]">
            <div class="flex flex-col items-center">
              <h3 class="text-x-black text-3xl font-bold leading-[40px] tracking-[-1px]">Jacob Jones</h3>
              <p class="text-x-mediumgrey leading-[28px] group-hover:text-white transition duration-200 ease-in-out">Content Writer @Company</p>
            </div>
            <ul class="flex items-center gap-6">
              <li>
                <a href="#">
                  <img src="@/assets/images/logo/facebook.png" alt="" class="hover:opacity-75 transition duration-150 ease-in-out">
                </a>
              </li>
              <li>
                <a href="#">
                  <img src="@/assets/images/logo/twitter.png" alt="" class="hover:opacity-75 transition duration-150 ease-in-out">
                </a>
              </li>
              <li>
                <a href="#">
                  <img src="@/assets/images/logo/instagram.png" alt="" class="hover:opacity-75 transition duration-150 ease-in-out">
                </a>
              </li>
              <li>
                <a href="#">
                  <img src="@/assets/images/logo/linkedin.png" alt="" class="hover:opacity-75 transition duration-150 ease-in-out">
                </a>
              </li>
            </ul>
          </div>
        </div>
      </section>
      <JoinContent />
  </MainLayout>
</template>
