<template>
  <div className="flex flex-col min-h-screen overflow-hidden">

    <!-- Site header -->
    <Header />

    <!-- Page content -->
    <main class="grow">

      <!-- Page sections -->
      <WofSingleHero />
      <Stats />
      <WofSingleContent />
      <RelatedStories />

    </main>
    
    <!-- Site footer -->
    <Footer />    

  </div>
</template>

<script>
import Header from '../partials/Header.vue'
import WofSingleHero from '../partials/WofSingleHero.vue'
import Stats from '../partials/Stats.vue'
import WofSingleContent from '../partials/WofSingleContent.vue'
import RelatedStories from '../partials/RelatedStories.vue'
import Footer from '../partials/Footer.vue'

export default {
  name: 'WallOfLoveSingle',
  components: {
    Header,
    WofSingleHero,
    Stats,
    WofSingleContent,
    RelatedStories,
    Footer,
},
}
</script>