<template>
  <div id="app">

    <MyHeader/>
    <MyJumbotron/>
    <MyContents/>
    <MySection/>
    <MyFooter/>
    <MyFootBar/>

  </div>
</template>

<script>
  import MyContents from './components/MyContents.vue';
  import MySection from './components/MySection.vue';
  import MyFooter from './components/MyFooter.vue';
  import MyFootBar from './components/MyFootBar.vue';
  import MyHeader from './components/MyHeader.vue'
  import MyJumbotron from './components/MyJumbotron.vue';







  export default {
    name: 'App',
    components: {
      MyContents,
      MySection,
      MyFooter,
      MyFootBar,
      MyHeader,
      MyJumbotron,
    
    }
  }
</script>

<style lang="scss">
  @import './style/general.scss'
</style>
