<template>
  <div>

    <TheHeader />
    <main>
      <ComicsSection />
    </main>

    <TheFooter />
  </div>
</template>

<script>
import TheHeader from './components/TheHeader.vue';
import TheFooter from './components/TheFooter.vue';
import ComicsSection from './components/ComicsSection.vue';


export default {
  name: 'DcComics',
  components: {
    TheHeader,
    ComicsSection,
    TheFooter,
  }

}
</script>

<style lang="scss">
@import "./assets/sass/style.scss";
</style>
