<template>
  <q-page class="flex flex-center">
    <sunburst-chart></sunburst-chart>
  </q-page>
</template>

<script>
import SunburstChart from 'components/SunburstChart.vue'
export default {
  name: 'PageIndex',
  components: { SunburstChart },
}
</script>
