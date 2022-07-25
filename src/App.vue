<template>
  <div>

    <TheHeader />
    <main>
      <TheJumbotron />
      <ComicsSection />
    </main>

    <TheFooter />
  </div>
</template>

<script>
import TheHeader from './components/TheHeader.vue';
import TheFooter from './components/TheFooter.vue';
import ComicsSection from './components/ComicsSection.vue';
import TheJumbotron from './components/TheJumbotron.vue';


export default {
  name: 'DcComics',
  components: {
    TheHeader,
    ComicsSection,
    TheFooter,
    TheJumbotron
  }

}
</script>

<style lang="scss">
@import "./assets/sass/style.scss";
</style>
