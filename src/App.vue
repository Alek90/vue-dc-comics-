<template>
  <div id="app">
    <HeaderSite />
    <MainSite />
    <FooterSite />
    
  </div>
</template>

<script>
import HeaderSite from './components/HeaderSite.vue'
import MainSite from './components/MainSite.vue'
import FooterSite from './components/FooterSite.vue'


export default {

  name: 'App',
  
  components: {
    HeaderSite,
    MainSite,
    FooterSite  
  }
}
</script>

<style lang="scss">

*{
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

#app{
  min-width: 1400px;
  max-width: 1600px;
  margin: auto;
  font-family: Greta Sans Bold, Arial,sans-serif;
}

.container{
  width: 70%;
  margin: auto;
}

</style>
