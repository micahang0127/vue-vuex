<template>
  <div id="app">
    <news-view></news-view>
    <count></count>
  </div>
</template>

<script>
import NewsView from './components/NewsView.vue'
import Count from './components/Count.vue'

export default {
  name: 'App',
  components: {
    NewsView,
    Count,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
