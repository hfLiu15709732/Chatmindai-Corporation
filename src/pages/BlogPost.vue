<template>
  <div className="flex flex-col min-h-screen overflow-hidden">

    <!-- Site header -->
    <Header />

    <!-- Page content -->
    <main class="grow">

      <!-- Page sections -->
      <BlogSingle />
      <div class="flex justify-center mb-8" aria-hidden="true">
        <svg class="fill-slate-400" height="4" width="36">
          <circle cx="18" cy="2" r="2" />
          <circle cx="2" cy="2" r="2" />
          <circle cx="34" cy="2" r="2" />
        </svg>
      </div>
      <Newsletter />

    </main>

    <!-- Site footer -->
    <Footer />

  </div>
</template>

<script>
import Header from '../partials/Header.vue'
import BlogSingle from '../partials/BlogSingle.vue'
import Newsletter from '../partials/Newsletter.vue'
import Footer from '../partials/Footer.vue'

export default {
  name: 'BlogPost',
  components: {
    Header,
    BlogSingle,
    Newsletter,
    Footer,
  },
}
</script>