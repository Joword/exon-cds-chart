<script lang="ts">
import { defineComponent } from 'vue';
import ExonCdsChart from '@/exon-cds-chart.vue';

export default defineComponent({
  name: 'ServeDev',
  components: {
    ExonCdsChart
  }
});
</script>

<template>
  <div id="app">
    <exon-cds-chart />
  </div>
</template>
