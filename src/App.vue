<template>
  <div id="app">
    <Header/>
    <Main/>
  </div>
</template>

<script>
import Header from './components/macro/Header.vue';
export default {
  name: 'App',
  components: {
    Header
  }
}
</script>

<style lang="scss">
@import './assets/img/style/global.scss';
</style>
