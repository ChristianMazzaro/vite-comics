<script>

  import mainHeader from './components/mainHeader.vue';
  import AppMain from './components/AppMain.vue';
  import MainFooter from './components/MainFooter.vue';

  export default {
    name: "App",
    components: {
      mainHeader,
      AppMain,
      MainFooter,
    },
    data(){
      return{

      }
    },
    methods: {

    }
  }
</script>

<template>

  <mainHeader />

  <AppMain />

  <MainFooter />

</template>

<style lang="scss">
@use "assets/scss/partials/reset";





</style>
