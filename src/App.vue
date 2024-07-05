<script>
import AppHeader from './components/AppHeader.vue';
import AppFooter from './components/AppFooter.vue';
import AppBlueSection from './components/AppBlueSection.vue';


export default {
  name: 'App',
  components: {
    AppHeader,
    AppFooter,
    AppBlueSection,
    
  }
}
</script>

<template>
  <AppHeader />
  <AppBlueSection />
  <AppFooter />

  
</template>

<style lang="scss">
@use './styles/general.scss' as *;
</style>
