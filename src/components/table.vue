<template lang="pug">
  div#table
    v-container.grey.lighten-5.mb-6
      v-row.border_title
        v-col title1
        v-col title2
        v-col title3
      v-row.border
        v-col value1
        v-col value2
        v-col value3
      v-row.border
        v-col value1
        v-col value2
        v-col value3
</template>
<script lang="ts">
import { defineComponent } from "@vue/composition-api";
export default defineComponent({
  // setup() {
  // },
});
</script>
<style scoped>
.border_title {
  border-bottom: 1px solid silver;
}
.border {
  border-bottom: 1px solid #e0e0e0;
}
</style>
