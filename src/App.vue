<template>
  <div id="app">
    <app-header :data="data"/>
  </div>
</template>

<script>
import data from './data.json';
import AppHeader from './components/AppHeader.vue';

export default {
  name: 'App',
  components: {
    AppHeader
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
