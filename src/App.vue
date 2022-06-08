<template>
  <div id="app">
    <HeaderBox />
    <FooterBox />
    <MainBox />
    <comp-main />
    <comp-main />
    <comp-main> </comp-main>
  </div>
</template>

<script>
import HeaderBox from './components/HeaderBox.vue';
import FooterBox from './components/FooterBox.vue';
import MainBox from './components/MainBox.vue';

export default {
  name: 'App',
  components: {
    HeaderBox,
    FooterBox,
    MainBox
  }
}

</script>

<style scoped>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
