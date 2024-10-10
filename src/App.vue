<script>
import AppHeader from './components/AppHeader.vue';
import AppFooter from './components/AppFooter.vue';

export default {
  components: {
    AppHeader,
    AppFooter
  }
}
</script>

<template>
  
  <section>
    <AppHeader></AppHeader>
    <router-view></router-view>
  </section>

</template>

<style lang="scss">

</style>
