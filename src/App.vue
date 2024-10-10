<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';

export default {
  components: {
    AppHeader,
    AppMain,
    AppFooter
  }
}
</script>

<template>
  
  <section>
    <AppHeader></AppHeader>
  </section>
  <section>
    <AppMain></AppMain>
  </section>
  <section>
    <AppFooter></AppFooter>
  </section>

</template>

<style>

</style>
