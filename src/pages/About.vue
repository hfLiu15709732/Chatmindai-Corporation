<template>
  <div className="flex flex-col min-h-screen overflow-hidden">

    <!-- Site header -->
    <Header />

    <!-- Page content -->
    <main class="grow">

      <!-- Page sections -->
      <AboutHero />
      <Stats02 />
      <AboutContent />
      <Team />
      <TeamMembers />
      <Clients02 />
      <Cta02 />

    </main>
    
    <!-- Site footer -->
    <Footer />    

  </div>
</template>

<script>
import Header from '../partials/Header.vue'
import AboutHero from '../partials/AboutHero.vue'
import Stats02 from '../partials/Stats02.vue'
import AboutContent from '../partials/AboutContent.vue'
import Team from '../partials/Team.vue'
import TeamMembers from '../partials/TeamMembers.vue'
import Clients02 from '../partials/Clients02.vue'
import Cta02 from '../partials/Cta02.vue'
import Footer from '../partials/Footer.vue'

export default {
  name: 'Home',
  components: {
    Header,
    AboutHero,
    Stats02,
    AboutContent,
    Team,
    TeamMembers,
    Clients02,
    Cta02,
    Footer,
  },
}
</script>