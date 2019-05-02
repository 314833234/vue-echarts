<template>
  <div id="app">
    <e-chart></e-chart>
    <!--<hand-table></hand-table>-->
    <slide-bar></slide-bar>
  </div>
</template>

<script>
import EChart from './components/EChart.vue'
//import HandTable from './components/HotTable.vue'
import SlideBar from './components/SlideBar.vue'

export default {
  name: 'app',
  components: {
    EChart,
    //HandTable,
    SlideBar
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
