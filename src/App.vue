<template>
  <div>

    <TheHeader />
    <TheMain />
  </div>
</template>

<script>
import TheHeader from './components/TheHeader.vue';
import TheMain from './components/TheMain.vue';


export default {
  name: 'DcComics',
  components: {
    TheHeader,
    TheMain,

  }

}
</script>

<style lang="scss">
@import "./assets/sass/style.scss";
</style>
