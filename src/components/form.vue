<template lang="pug">
  div#form
    v-card-title
      h1 検索する
    v-card-text
      v-form
        v-text-field(
          prepend-icon="mdi-magnify",
          label="例）軽井沢 おしゃれ",
          width="80%")
      v-card-actions
        v-btn 検索
</template>
<script lang="ts">
import { defineComponent } from "@vue/composition-api";
export default defineComponent({
  setup() {
  },
});
</script>
<style scoped>
</style>
