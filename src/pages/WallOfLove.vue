<template>
  <div className="flex flex-col min-h-screen overflow-hidden">

    <!-- Site header -->
    <Header />

    <!-- Page content -->
    <main class="grow">

      <!-- Page sections -->
      <WofHero />
      <Clients />
      <Customers />
      <Testimonials />
      <CtaDark />

    </main>
    
    <!-- Site footer -->
    <Footer />    

  </div>
</template>

<script>
import Header from '../partials/Header.vue'
import WofHero from '../partials/WofHero.vue'
import Clients from '../partials/Clients.vue'
import Customers from '../partials/Customers.vue'
import Testimonials from '../partials/Testimonials.vue'
import CtaDark from '../partials/CtaDark.vue'
import Footer from '../partials/Footer.vue'

export default {
  name: 'WallOfLove',
  components: {
    Header,
    WofHero,
    Clients,
    Customers,
    Testimonials,
    CtaDark,
    Footer,
},
}
</script>