<template>
  <section class="flex flex-col gap-8 bg-white px-[80px] py-[40px]">
    <h2 class="text-x-black text-4xl text-center font-bold leading-[48px] tracking-[-2px]">List of Authors</h2>
    <!-- Menggunakan grid untuk 2 kolom dan 4 baris -->
    <div class="grid grid-cols-2 gap-6">
      <AuthorCard
        v-for="(author, index) in authors"
        :key="index"
        :authorImage="author.image"
        :authorName="author.name"
        :authorDescription="author.description"
        :socialLinks="author.socialLinks"
      />
    </div>
  </section>
</template>

<script>
export default {
  name: 'AuthorsSection',
  data() {
    return {
      authors: [
        {
          image: '@/assets/images/misc/author-1.png',
          name: 'Floyd Miles',
          description: 'Content Writer @Company',
          socialLinks: [
            { icon: '@/assets/images/logo/facebook.png', url: '#' },
            { icon: '@/assets/images/logo/twitter.png', url: '#' },
            { icon: '@/assets/images/logo/instagram.png', url: '#' },
            { icon: '@/assets/images/logo/linkedin.png', url: '#' }
          ]
        },
        {
          image: '@/assets/images/misc/author-2.png',
          name: 'Dianne Russell',
          description: 'Content Writer @Company',
          socialLinks: [
            { icon: '@/assets/images/logo/facebook.png', url: '#' },
            { icon: '@/assets/images/logo/twitter.png', url: '#' },
            { icon: '@/assets/images/logo/instagram.png', url: '#' },
            { icon: '@/assets/images/logo/linkedin.png', url: '#' }
          ]
        },
        {
          image: '@/assets/images/misc/author-3.png',
          name: 'Jenny Wilson',
          description: 'Content Writer @Company',
          socialLinks: [
            { icon: '@/assets/images/logo/facebook.png', url: '#' },
            { icon: '@/assets/images/logo/twitter.png', url: '#' },
            { icon: '@/assets/images/logo/instagram.png', url: '#' },
            { icon: '@/assets/images/logo/linkedin.png', url: '#' }
          ]
        },
        {
          image: '@/assets/images/misc/author-4.png',
          name: 'Leslie Alexander',
          description: 'Content Writer @Company',
          socialLinks: [
            { icon: '@/assets/images/logo/facebook.png', url: '#' },
            { icon: '@/assets/images/logo/twitter.png', url: '#' },
            { icon: '@/assets/images/logo/instagram.png', url: '#' },
            { icon: '@/assets/images/logo/linkedin.png', url: '#' }
          ]
        }
        // Tambahkan 6 objek data penulis lainnya di sini
      ]
    }
  },
  components: {
    AuthorCard: {
      props: {
        authorImage: String,
        authorName: String,
        authorDescription: String,
        socialLinks: Array
      },
      template: `
        <div class="w-[296px] bg-x-lightgrey flex flex-col items-center justify-center gap-4 p-6 hover:bg-x-lightyellow hover:cursor-pointer transition duration-200 ease-in-out">
          <img :src="authorImage" :alt="'Foto ' + authorName" class="w-[128px] h-[128px]">
          <div class="flex flex-col items-center">
            <h3 class="text-x-black text-3xl font-bold leading-[40px] tracking-[-1px]">{{ authorName }}</h3>
            <p class="text-x-mediumgrey leading-[28px] group-hover:text-white transition duration-200 ease-in-out">{{ authorDescription }}</p>
          </div>
          <ul class="flex items-center gap-6">
            <li v-for="(link, index) in socialLinks" :key="index">
              <a :href="link.url" target="_blank">
                <img :src="link.icon" alt="" class="hover:opacity-75 transition duration-150 ease-in-out">
              </a>
            </li>
          </ul>
        </div>
      `
    }
  }
}
</script>
