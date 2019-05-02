<template>
  <div>
    <hot-table :id="id" :class="className" :style="style" :settings="hotSettings"></hot-table>
  </div>
</template>

<script>
import { HotTable } from '@handsontable/vue';

export default {
  name: 'HotTable',
  components: {
    HotTable
  },
  data() {
    return {
      hotSettings: {
        startRows: 5,
        startCols: 5,
        colHeaders: true,
        stretchH: 'all'
      },
      id: 'my-custom-id',
      className: 'my-custom-classname',
      style: 'width: 300px; height: 142px; overflow: hidden; border: 1px solid red;'
    }
  }
}
</script>
