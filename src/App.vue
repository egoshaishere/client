<template>
  <div id="app">
    <Header />
    <Content />
    <footer-flex />
  </div>
</template>

<script>
import Header from './components/Header.vue';
import Content from './components/Content.vue';
import footerFlex from './components/Footer.vue';
export default {
  name: 'App',
  components: {
    Header,
    Content,
    footerFlex
  }
}
</script>

<style>
body {
  margin: 0;
}
</style>
