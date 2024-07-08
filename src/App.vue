<script>
import AppHeader from './components/AppHeader.vue';
import AppFooter from './components/AppFooter.vue';
import AppBlueSection from './components/AppBlueSection.vue';
import AppContent from './components/AppContent.vue';



export default {
  name: 'App',
  components: {
    AppHeader,
    AppFooter,
    AppBlueSection,
    AppContent,
    
  }
}
</script>

<template>
  <AppHeader />
  <main>
    <AppContent />
  </main>
  <AppBlueSection />
  <AppFooter />

  
</template>

<style lang="scss">
@use './styles/general.scss' as *;
@use './styles/partials/mixins' as*;
@use './styles/partials/variables' as*;
</style>
