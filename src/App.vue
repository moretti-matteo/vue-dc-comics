<template>
  <div id="app">
    <BaseHeader></BaseHeader>
    <BaseMain></BaseMain>
    <BaseFooter></BaseFooter>
  </div>
</template>

<script>
import BaseHeader from './components/BaseHeader.vue';
import BaseMain from './components/BaseMain.vue';
import BaseFooter from './components/BaseFooter.vue';

export default {
  name: 'App',
  components: {
    BaseHeader,
    BaseMain,
    BaseFooter
  }
}
</script>

<style lang="scss">
@import "./assets/style/variables.css";
@import "./assets/style/global.css";
</style>
