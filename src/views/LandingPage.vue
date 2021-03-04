<template>
  <div class="LandingPage">
    <navbar />
    <headerSection />
    <footerSection />
  </div>
</template>

<script>
import navbar from '../components/_base/LandingPageComponent/navigationBarLP'
import headerSection from '../components/_base/LandingPageComponent/HeaderSection'
import footerSection from '../components/_base/LandingPageComponent/footerBarLP'
export default {
  name: 'LandingPage',
  components: {
    navbar,
    headerSection,
    footerSection
  },
  data() {
    return {}
  }
}
</script>
<style scoped>
.LandingPage {
  background: url('../assets/Images/SecondaryThema/HeaderWafeLandingPage.svg');
  height: 100vh;
  background-repeat: no-repeat;
}
</style>
