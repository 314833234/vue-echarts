<template>
  <div id="app">
    <e-chart></e-chart>
    <hot-table></hot-table>
  </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
/*import ECharts from 'vue-echarts'
import 'echarts/lib/chart/bar'
import 'echarts/lib/component/tooltip'*/
import EChart from './components/EChart.vue'
//import HotTable from './components/HotTable.vue'



export default {
  name: 'app',
  components: {
    EChart,
    //HotTable
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
