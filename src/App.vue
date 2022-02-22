<template>
  <div id="app">
      <MyHeader></MyHeader>
      <MyMain></MyMain>
      <MyFooterFirst></MyFooterFirst>
      <MyFooterSecond></MyFooterSecond>
      <MyFooterThird></MyFooterThird>
  </div>
</template>

<script>
import MyHeader from './components/MyHeader.vue'
import MyMain from './components/MyMain.vue'
import MyFooterFirst from './components/MyFooterFirst.vue'
import MyFooterSecond from './components/MyFooterSecond.vue'
import MyFooterThird from './components/MyFooterThird.vue'

export default {
  name: 'App',
  components: {
    MyHeader,
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
