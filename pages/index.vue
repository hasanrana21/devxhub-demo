<template>
  <section>
    <Banner></Banner>
    <Companies> </Companies>
    <Services> </Services>
    <TechnologyUsed></TechnologyUsed>
  </section>
</template>

<script>
import Banner from '../components/Home/Banner.vue'
import Companies from '../components/Home/Companies.vue'
import Services from '../components/Home/Services.vue'
import TechnologyUsed from '../components/Home/TechnologyUse.vue'
export default {
  components: { Banner, Companies, Services, TechnologyUsed },
}
</script>
