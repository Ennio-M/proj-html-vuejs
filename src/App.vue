<template>
  <div id="app">
    <app-header :data="data"/>
    <app-main :data="data"/>
  </div>
</template>

<script>
import data from './data.json';
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';

export default {
  name: 'App',
  components: {
    AppHeader,
    AppMain
  },
  data() {
    return {
      data: data
    }
  }
}
</script>

<style lang="scss">
  @import './styles/general.scss';
</style>
