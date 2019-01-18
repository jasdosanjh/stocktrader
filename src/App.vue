<template>
  <div class="container">
    <app-header></app-header>
    <div class="row">
        <div>
            <router-view></router-view>
        </div>
    </div>
  </div>
</template>

<script>
import Header from './components/Header.vue'
export default {
  components: {
    appHeader: Header
  },
  created() {
    this.$store.dispatch('initStocks');
  }
}
</script>

<style lang="scss">
body {
  background: #EEE;
}
</style>
