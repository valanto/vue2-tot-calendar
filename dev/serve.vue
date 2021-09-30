<script lang="ts">
import Vue from 'vue';
import Vue2TotCalendar from '@/vue2-tot-calendar.vue';

export default Vue.extend({
  name: 'ServeDev',
  components: {
    Vue2TotCalendar
  }
});
</script>

<template>
  <div id="app">
    <vue2-tot-calendar />
  </div>
</template>
