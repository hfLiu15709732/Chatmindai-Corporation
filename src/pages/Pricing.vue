<template>
  <div className="flex flex-col min-h-screen overflow-hidden">

    <!-- Site header -->
    <Header />

    <!-- Page content -->
    <main class="grow">

      <!-- Page sections -->
      <PricingHero />
      <PricingCta />
      <PricingFeatures />
      <FeaturesTable />
      <Faqs />
      <CtaDark />

    </main>
    
    <!-- Site footer -->
    <Footer />    

  </div>
</template>

<script>
import Header from '../partials/Header.vue'
import PricingHero from '../partials/PricingHero.vue'
import PricingCta from '../partials/PricingCta.vue'
import PricingFeatures from '../partials/PricingFeatures.vue'
import FeaturesTable from '../partials/FeaturesTable.vue'
import Faqs from '../partials/Faqs.vue'
import CtaDark from '../partials/CtaDark.vue'
import Footer from '../partials/Footer.vue'

export default {
  name: 'Pricing',
  components: {
    Header,
    PricingHero,
    PricingCta,
    PricingFeatures,
    FeaturesTable,
    Faqs,
    CtaDark,
    Footer,
  },
}
</script>