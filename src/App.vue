<template>
  <div id="app">
      <MyHeader></MyHeader>
      <MyJumbotron></MyJumbotron>
      <MyMain></MyMain>
      <MyFooterFirst></MyFooterFirst>
      <MyFooterSecond></MyFooterSecond>
      <MyFooterThird></MyFooterThird>
  </div>
</template>

<script>
import MyHeader from './components/MyHeader.vue'
import MyJumbotron from './components/MyJumbotron.vue'
import MyMain from './components/MyMain.vue'
import MyFooterFirst from './components/MyFooterFirst.vue'
import MyFooterSecond from './components/MyFooterSecond.vue'
import MyFooterThird from './components/MyFooterThird.vue'

export default {
  name: 'App',
  components: {
    MyHeader,
    MyJumbotron,
    MyMain,
    MyFooterFirst,
    MyFooterSecond,
    MyFooterThird
  }
}
</script>

<style lang="scss">

  @import "./assets/style/generals.scss";

</style>
