<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';

export default {
  name: 'App',
  components: {
    AppHeader,
    AppMain

  },


}
</script>

<template>
  <AppHeader />

  <RouterView></RouterView>
</template>

<style lang="scss">
@use './styles/general.scss' as *;
@use 'bootstrap/scss/bootstrap' as *;
</style>
