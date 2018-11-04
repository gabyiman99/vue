<template>
  <div id="app">
    <Header/>
    <!--<Main/>-->
    <PlafonCashLoan/>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Main from './components/Main.vue'
import PlafonCashLoan from './components/PlafonCashLoan.vue'

export default {
  name: 'app',
  components: {
    Header, Main, PlafonCashLoan
  }
}
</script>
<style lang="stylus">
#app
  font-family 'Avenir', Helvetica, Arial, sans-serif
  -webkit-font-smoothing antialiased
  -moz-osx-font-smoothing grayscale
  text-align center
  color #2c3e50
  margin-top 0
</style>
