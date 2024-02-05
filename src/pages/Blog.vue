<template>
  <div className="flex flex-col min-h-screen overflow-hidden">

    <!-- Site header -->
    <Header />

    <!-- Page content -->
    <main class="grow">

      <!-- Page sections -->
      <BlogHero />
      <BlogTags />
      <BlogList />

    </main>
    
    <!-- Site footer -->
    <Footer />    

  </div>
</template>

<script>
import Header from '../partials/Header.vue'
import BlogHero from '../partials/BlogHero.vue'
import BlogTags from '../partials/BlogTags.vue'
import BlogList from '../partials/BlogList.vue'
import Footer from '../partials/Footer.vue'

export default {
  name: 'Blog',
  components: {
    Header,
    BlogHero,
    BlogTags,
    BlogList,
    Footer,
  },
}
</script>