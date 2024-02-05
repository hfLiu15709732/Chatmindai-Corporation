<template>
  <div className="flex flex-col min-h-screen overflow-hidden">

    <!-- Site header -->
    <Header />

    <!-- Page content -->
    <main class="grow">

      <!-- Page sections -->
      <SupportHero />
      <SupportContent />

    </main>

    <!-- Site footer -->
    <Footer />

  </div>
</template>

<script>
import Header from '../partials/Header.vue'
import SupportHero from '../partials/SupportHero.vue'
import SupportContent from '../partials/SupportContent.vue'
import Footer from '../partials/Footer.vue'

export default {
  name: 'Support',
  components: {
    Header,
    SupportHero,
    SupportContent,
    Footer,
  },
}
</script>